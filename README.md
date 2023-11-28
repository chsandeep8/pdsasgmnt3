# PDS ASSIGNMENT 3
**prerequisites**:
google collab 
**Given**
1) The data file diabetes.csv contains data from 768 patients. In this data, there are 8 attributes (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age) and 1 response variable (Outcome). The response variable, Outcome, has a binary value (1 indicating the outcome is diabetes and 0 means no diabetes)
   
**Getting Started**  
- Imported all required packages
- Reading data
- Checking info on the data
- checking nulls
- all these above steps give us a basic understanding of data

a)  set a seed (to ensure work reproducibility) and take a random sample of  25 observations and find the mean Glucose and highest Glucose values of this sample and compare these statistics with the population statistics of the same variable. You should use charts for this comparison.
- Setting a seed value
- Taking a sample of 25 observations
- Plotting the comparison of sample and population data on mean and highest of glucose
![image](https://github.com/chsandeep8/pdsasgmnt3/assets/50614267/b76e5630-7c44-4f9e-b2f5-2356d8ba17eb)


b) Find the 98th percentile of BMI of your sample and the population and compare the results using charts.
- calculating 98th percentile for BMI
- plotting the comparision between sample and population data for 98th percentile of BMI using row chart
  ![image](https://github.com/chsandeep8/pdsasgmnt3/assets/50614267/71596bed-7bc0-442f-a413-6c4a64d49538)


c) Using bootstrap (replace= True), create 500 samples (of 150 observations each) from the population and find the average mean, standard deviation and percentile for BloodPressure and compare this with these statistics from the population for the same variable.
- bottstraping
- calculating mean , standard deviation and 98th percentile for bootstraped data
- plotting comprasion
- ![image](https://github.com/chsandeep8/pdsasgmnt3/assets/50614267/f188cf55-1246-4832-9838-70cb15e011b0)
- **Findings** :
- after bootsraping we can clearly see that both sample and population of Mean of Blood Pressure , standard deviation of BP are almost same and 95th percentile has little differnce still better than random sample vs population comparsion so this clearly shows that bootsrapping works better than random sampling to make a decision on data



