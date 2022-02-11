# [Credir Risk Analysis]

**[Nesma Dehili]**

**[IronHack, Paris 11 Feb 2022]**

## Overview

Include the following points in your overview:

* How banks can maximize profit by minimzing risk of default?
	
Used:

	* Python
	* Statistical analysis
	* Data visualization
	* Jupyter Notebook
	* Tableau
	* Machine Learning ( Logistic Regression, Gardient boost classifier,Random forest classifier, TPOT)


## Data Preparation

### Overview:

* Data is about client information and loan info.
	* [https://www.kaggle.com/sriricky/finance-banking-predication]
* 19 columns 
* 110 000 rows 
* columns:
- Customer ID, 
- Credit Score,  
- Annual Income,  
- Years in current job, 
- Home Ownership, Purpose, 
- Years of Credit History,
- Months since the last delinquent, 
- Number of Open Accounts,
- Number of Credit Problems,
- Maximum Open Credit, Bankruptcies, Tax Liens
- Loan ID
- Loan Status
- Current Loan Amount
- Term
- Monthly Debt
- Current Credit Balance

### Data Wrangling and Cleaning
- Overall Data description
- Deleting  11081 duplicates 
- Looking for outliers column by column 
- Dropping columns with more than 50% nan values 
- Dropping  NaN values from the target column 
- Interpolating empty cells 

### Data Storage

* Dump your data as `.csv` file.

## Data Analysis
* Use tableau to analyze 
* 
### Data Exploration and Visualization

Used Tableau to visualize my overall data.

### Model Training and Evaluation

- Encoding 
- Feature Selection 
- Hyperparameter tuning
- Models 
- Compared accuracy 
- AUC-ROC Curve
- Checking Calibration

## Data Strategy: 
* Banks need to define a strategy by defining the percentage of loans granted with the goal of keeping defaults below a certain rate
### Overview
- Defining acceptance rate 
- Defining limit probability
- Assessing error rate
- Calculating accepted loans
- Estimating the portfolio value
- Finding the BEST combination 

## Conclusion
- Based on the acceptance rate, we can calculate our risk limit, error rate (risk within the accepted loans), number of loans given and the mazimized portfolio value. 
- Our model had an accuracy od 70% 
