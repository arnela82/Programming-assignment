---
title: "CodeBook.md"
author: "arnela82"
date: "3/22/2020"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
Getting and Cleaning Data - peer assessment project
The original data was transformed by
Merging the training and the test sets to create one data set.
Extracting only the measurements on the mean and standard deviation for each measurement.
Using descriptive activity names to name the activities in the data set
Appropriately labeling the data set with descriptive activity names.
Creating a second, independent tidy data set with the average of each variable for each activity and each subject.
About R script
File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work)

About variables:
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored in
## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
