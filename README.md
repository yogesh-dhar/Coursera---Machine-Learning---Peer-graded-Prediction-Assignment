# Coursera---Machine-Learning---Peer-graded-Prediction-Assignment
## Overview

The goal of this project is to predict the manner in which 6 participants did various exercises. There is a "classe" variable available in the training set. I have created a report describing how I built my model and used cross validation, what I think the expected out of sample error is, and why I made the choices I had to. I will also use my prediction model to predict 20 different test cases.


## Summary

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).


## Data Source

The training data for this project is available here:
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data is available here:
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

The data for this project come from this source: http://groupware.les.inf.puc-rio.br/har. I would like to specially thank following persons for their permission to allow me to use their data for my assignment.
Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013.

## Steps Involved in entire process are given below:
  ## Download, Read and Clean Data
  ## Model Building and Assessment
    ### Load Required Packages
    ### Data Partition (Training and Testing dataset)
    ### Approach to Prediction models
    ### Cross validation
    ### The codes required to build our predictive models are given below:
      ### Method = Recursive Partitioning and Regression Trees (rpart)
      ### Method = Generalized Boosted Models (gbm)
      ### Method = Random Forest Decision Trees (rf)
      ### Method = Boosted Logistic Regression (LogitBoost)
## Visualising Model performances and Concluding
    
