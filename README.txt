German Bank Loan Default Prediction


**Project Overview:**
This project aims to predict loan defaults using historical data from customers of a German bank. The dataset includes various attributes of customers who have taken loans, such as account balances, credit history, loan details, and personal demographics. By applying machine learning techniques, this project seeks to aid the bank by predicting if a customer would default or not based on the historical data.


**Dataset:**
The German_bank.csv file contains data on 1000 customers with the following key attributes:
- Checking & savings account balances
- Loan duration & amount
- Loan purpose & credit history
- Employment details like job type, duration of employment & percentage of monthly income
- Personal demographics like age, number of dependents & phone usage (yes/no)
- Other details like duration at current residence, type of housing, other credits taken & number of credits and default status  

Each entry represents a unique customer, providing a comprehensive view of their personal, professional, financial status and credit history.


**Project Structure:**
The project is organised into several key components:
- README.txt: The current file you are reading giving an overview of the project.
- German_bank.csv: The loan default dataset that is provided. 
- Final Project - Sundar Ram Subramanian.ipynb: This is the python code notebook (Jupyter notebook) that detail the following: 
	1. Library Import: 
		-> Setting up your Python environment with necessary libraries.
	2. Data Ingestion: 
		-> Loading the dataset into your workspace.
	3. Exploratory Data Analysis (EDA): Assessing data quality and characteristics through:
		-> Overview and statistical summaries.
   		-> Null value checks.
   		-> Analysis of class balance.
   		-> Correlation between features through visualisation plots like heatmap & pair plot for multicollinearity & correlation insights.
   		-> Histograms for distribution insights.
   		-> Outlier Analysis.
	4. Data Preprocessing:
   		-> Encoding categorical variables.
   		-> Scaling numerical data to standardise features.
	5. ML Model Building and Optimization:
   		-> Splitting data into training and testing sets.
   		-> Initial model fitting with basic parametric and tree-based models, including cross-validation.
   		-> Hyper-parameter tuning of the most promising models.
   		-> Feature importance analysis to refine model inputs.
   		-> Re-evaluation using only the important features (a reduced feature set).
   		-> Combining best individual models into an ensemble for improved performance.
	6. ML Model Recommendation: 
		-> Analysing and comparing model performances to choose the best model for deployment.
- Final Project - Sundar Ram Subramanian.html: .html version of the Jupyter notebook
- Final Report - German Bank Loan - Sundar Ram Subramanian.pdf: Final Report in PDF format with Introduction, Methods and Materials, Results, Discussion & Conclusion.


**Installation:**
To set up the project environment and install the necessary library packages, run the following command in your terminal:

```pip install pandas numpy matplotlib seaborn scikit-learn```

It is recommended to use a virtual environment.

**Usage:**
Ensure that German_bank.csv and Final Project - Sundar Ram Subramanian.ipynb are in the same directory.
The Jupyter Notebook is optimised to work in any Notebook IDE after installation of the required packages.

