Quiz 1 distribution
========================================================
Before starting an R session, you must call up the R-packages needed for your analysis.


```r
library(plyr)
library(ggplot2)
```


Set working directory

```r
setwd("/Users/Deborah/desktop/CENG340/grade_dist")
```


Read in data

```r
# To import data
abc <- read.table("quiz1.csv", header = FALSE, sep = ",")
```


I also looked at the data to make sure it was input correctly.


```r
abc
```

```
##      V1
## 1   4.5
## 2   9.0
## 3   6.0
## 4   7.0
## 5   9.0
## 6  10.0
## 7   5.0
## 8   4.0
## 9   9.5
## 10  5.0
## 11 10.0
## 12  5.5
## 13 10.0
## 14  9.0
## 15  6.5
## 16  6.5
## 17 10.0
## 18  7.0
## 19  5.0
## 20  8.5
## 21  4.0
## 22  9.0
## 23  5.0
## 24  5.0
## 25  5.0
## 26 10.0
## 27  4.0
## 28  8.5
## 29 10.0
## 30  9.0
## 31  8.0
## 32  7.0
## 33  9.0
## 34  4.0
## 35  8.0
## 36  9.0
## 37 10.0
## 38  5.0
## 39  8.5
## 40  8.0
## 41  6.0
## 42  6.0
## 43  7.5
```


Plot prob density



