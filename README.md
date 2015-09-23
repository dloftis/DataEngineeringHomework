# DataEngineeringHomework

## Setup (Optional)
1.  Fork this repository to your GitHub account
2.  Clone this repository to you desktop

## Task
In this exercise, you will be asked to analyze the data set in the [activity.csv](https://github.com/dloftis/DataEngineeringHomework/blob/master/activity.csv) file.

For the purposes of this analysis you must...

1.  Run all analysis in Spark 
2.  Write all analysis code in Scala
3.  Use RDDs for the analysis.  _For bonus points, you can repeat the analysis using DataFrames._

Output of the analysis is completely up to you.  At the bare minimum, command line output will work.  _For bonus points, you can use a plotting package._

## Data
This data set is a publically avaliable dataset from personal monitoring devices (like: Nike Fuelbank, Jawbone Up, Fitbit, etc).  These devices collect data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and includes the number of steps taken in 5 minute intervals each day.

Dataset Description: Activity monitoring data

The variables included in this dataset are:

__steps__: Number of steps taking in a 5-minute interval with 0 being the start of the day and higher values being evening (missing values are coded as NA)

__date__: The date on which the measurement was taken in YYYY-MM-DD format

__interval__: Identifier for the 5-minute interval in which measurement was taken

The dataset is stored in a comma-separated-value (CSV) file and there are a total of 17,568 observations in this dataset.

## Analysis
### Part 1
With the above dataset, please answer the following basic questions:

1.  How many the total number of rows that are missing data out of the dataset?  What percentage of the data set is this?
2.  Ignoring missing data, what is the mean number of steps taken daily? (Answer is a single value)
3.  Ignoring missing data, within each day, what is the average number of steps taken / interval? (Answer is 1 value for each day we have measurements)
4.  Ignoring missing data, what is the mean number of steps taken for each interval over all days? (Answer should be 1 value for each interval identifier)

### Part 2
With the data set, impute the missing NA values and if that has any affect on the outcoem of our analysis.

1.  Impute missing values by replacing the 'NA' with some approximation.  Make sure you comment what you did to impute the missing values.  The approximation is your choice.  A couple of suggestions would be the average number of steps taken per interval that day, or the average number of steps per interval over all 3 days.  
2.  What is the mean number of steps taken daily? (Answer is a single value)
3.  Within each day, what is the average number of steps taken / interval? (Answer is 1 value for each day)
4.  What is the mean number of steps taken for each interval over all days? (Answer should be 1 value for each interval identifier)

## Submission
When you are finished with this assignment, submit a link to your personal GitHub reppository with all Scala code needed to exectue this assignment.  The code can be in one or more files.

