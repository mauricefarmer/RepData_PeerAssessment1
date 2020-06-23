# Reproducible Research - Course Project 1

## Introduction

It is now possible to collect a large amount of data about personal movement using activity monitoring devices such as a Fitbit, Nike Fuelband, or Jawbone Up. These type of devices are part of the “quantified self” movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. But these data remain under-utilized both because the raw data are hard to obtain and there is a lack of statistical methods and software for processing and interpreting the data.

This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November 2012 and include the number of steps taken in 5 minute intervals each day.

	
The goal is to make analytic data and code available so that others may reproduce findings .

## Input File
	The following input file was provided in the assigment.

	* 'activity.csv'
    
    The variables included in this dataset are:

    steps: Number of steps taking in a 5-minute interval (missing values are coded as 
    NA
    NA)
    date: The date on which the measurement was taken in YYYY-MM-DD format
    interval: Identifier for the 5-minute interval in which measurement was taken
The dataset is stored in a comma-separated-value (CSV) file and there are a total of 17,568 observations in this dataset.


## Processing Steps
	The detailed steps used for this project are captured in PA1_template.Rmd. 
	
	There is always more than one way to implement a process.  
	Some of my coding decisions were very basic and simple. 
	I know as time goes on and I gain more experience in R, then how I write code will also improve.
	
	The project provided the following goals.
		1.	Code for reading in the dataset and/or processing the data
		2.	Histogram of the total number of steps taken each day
		3.	Mean and median number of steps taken each day
		4.	Time series plot of the average number of steps taken
		5.	The 5-minute interval that, on average, contains the maximum number of steps
		6.	Code to describe and show a strategy for imputing missing data
		7.	Histogram of the total number of steps taken each day after missing values are imputed
		8.	Panel plot comparing the average number of steps taken per 5-minute interval across weekdays and weekends
		9.	All of the R code needed to reproduce the results (numbers, plots, etc.) in the report

				
## Output Files

	* README.md
		This is the file you are currently reading

	* PA1_template.Rmd
		This contains the code and steps.

	* PA1_template.md
		This is created by running with knit2html() function in R (from the knitr package) by running the function from the console.

	* PA1_template.htm
		This is created by running with knit2html() function in R (from the knitr package) by running the function from the console.
		
