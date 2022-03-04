# ReneWind
## Business Problem
An energy company working on improving the machinery/processes involved in the production of wind energy using machine learning and has collected data of generator failure of wind turbines using sensors. They have shared a ciphered version of the data, as the data collected through sensors is confidential (the type of data collected varies with companies). Data has 40 predictors, 20000 observations in the training set, and 5000 in the test set.  The objective is to build various classification models, tune them, and find the best one that will help identify failures so that the generators could be repaired before failing/breaking to reduce the overall maintenance cost. 

The nature of predictions made by the classification model will translate as follows:  
* True positives (TP) are failures correctly predicted by the model. These will result in repair costs. 
* False negatives (FN) are real failures where there is no detection by the model. These will result in replacement costs. 
* False positives (FP) are detections where there is no failure. These will result in inspection costs. 

It is given that the cost of repairing a generator is much less than the cost of replacing it, and the cost of the inspection is less than the cost of repair.  
“1” in the target variables should be considered as “failure” and “0” represents “No failure”.   
  
## Data Description  
The data provided is a transformed version of original data which was collected using sensors. 
Train.csv - To be used for training and tuning of models.  
Test.csv - To be used only for testing the performance of the final best model. 

Both the datasets consist of 40 predictor variables and 1 target variable
