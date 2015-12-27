# Practical Machine Learning Course Project

## Problem

##### Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: 


##### http://groupware.les.inf.puc-rio.br/har 
##### (see the section on the Weight Lifting Exercise Dataset). 

## Data Set

##### The data for this project come from this source: http://groupware.les.inf.puc-rio.br/har. If you use the document you create for this class for any purpose please cite them as they have been very generous in allowing their data to be used for this kind of assignment. 


##### The training data for this project are available here: 

##### https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

##### The test data are available here: 

##### https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

## Required Libraries

##### The following R libraries are required to run this project.

1. rlist
2. caret
3. data.table
4. dplyr
5. randomForest
6. ggplot2
7. parallel
8. doParallel

## Project Files

1. PML_Project.Rmd
2. PML_Project.html
3. pml-training.csv
4. pml-testing.csv

## Sub Folders

##### The predictions for the 20 test cases are located in the predictions subfolder

1. predictions
2. PML_Project_cache
3. PML_Project_files

## Run Time Configuration

##### This analysis was performed on an 8 core workstation with 32GB of RAM. At its peak, the analysis consumed nearly 10GB of RAM. If the reader were to run this analysis, please do so on a workstation with enough memory. The parallel library was used to exploit multiple cores in the analysis. If the reader were to run this analysis, please adjust the number of clusters/core to match your workstation's specification. The following libraries below are required for this analysis.