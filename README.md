## Accelerometers Data Project
####Course Project:

The purpose of this README.md is to give a brief description of this project, its goals and to briefly describe the scripts and their functions towards the dataset.

This project is an exercise to demonstrate my ability to collect, work with, and clean a data set. I have prepared a tidy data that can be used for later analysis. This repo will contain a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data, its called CodeBook.md. 

####Background:

"One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:"* 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

####Data Set:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

####Script:
Using Rstudio I created a script called run_analysis.R which maniuplated and tidied up the data set in order to meet the goals of the project. It script executes in this following order:

1. Merged the training and the test sets to create one data set.
2. Extracted only the measurements on the mean and standard deviation for each measurement. 
3. Used descriptive activity names for the activities in the data set.
4. Labeled the data set with descriptive variable names. 
5. Created an independent second data set with the average of each variable for each activity and each subject.

*Source: https://class.coursera.org/getdata-035/human_grading/view/courses/975119/assessments/3/submissions
