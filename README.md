# Standerized Testing Analysis
## Description
In this project we will look into standerized testing's relationships with factors such as salary, education, etc.

## Data
The data sets we will be using are:  
EdGap_data.xlsx - https://www.edgap.org  
ccd_sch_029_1617_w_1a_11212017.csv - https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0  
Since the ccd_sch dataset is too large to place into github, it can be accsess through the dropbox link instead.

## Data Preperation - Li_Education_Inequality_Data_Preparation.ipynb
We cleaned the data, taking all the data with proper values. After selecting the interesting columns we then joined them to create a single dataframe. We have also seperated the data into training and test sets. We then create the clean data file: clean_education_inequality.csv

## Data Analysis - Li_Education_Inequality_Analysis.ipynb
We observed each variable and found the best subset by comparing different combinations of the variables. After selecting the best model based on adjusted r-squared, BIC and AIC values we tested its effectiveness.
