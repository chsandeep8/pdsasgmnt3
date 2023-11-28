# PDS ASSIGNMENT 3
**prerequisites**:
google collab 
**Given **
1) The data file diabetes.csv contains data of 768 patients. In this data there are 8 attributes (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age) and 1 response variable (Outcome). The response variable, Outcome, has a binary value (1 indicating the outcome is diabetes and 0 means no diabetes)
   
**Getting Started**  
> Imported all required packages
> Reading data
> Checking info on the data
> checking nulls
all these above steps give us a basic understanding of data

a)  set a seed (to ensure work reproducibility) and take a random sample of  25 observations and find the mean Glucose and highest Glucose values of this sample and compare these statistics with the population statistics of the same variable. You should use charts for this comparison.
> Setting a seed value
> Taking a sample 0f 25 observations
> plotting 

b) Find the 98th percentile of BMI of your sample and the population and compare the results using charts.


c) Using bootstrap (replace= True), create 500 samples (of 150 observations each) from the population and find the average mean, standard deviation and percentile for BloodPressure and compare this with these statistics from the population for the same variable.
