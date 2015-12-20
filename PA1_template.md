# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```r
rawData <- read.csv("activity/activity.csv", header = TRUE, sep = ",")
index <- complete.cases(rawData)
data <- rawData[index,]
```


## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
