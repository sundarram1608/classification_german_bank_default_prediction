# German Bank Loan Default Prediction


**Project Overview:**<br>
This project aims to predict loan defaults using historical data from customers of a German bank. The dataset includes various attributes of customers who have taken loans, such as account balances, credit history, loan details, and personal demographics. By applying machine learning techniques, this project seeks to aid the bank by predicting if a customer would default or not based on the historical data.


**Dataset:**<br>
The German_bank.csv file contains data on 1000 customers with the following key attributes:<br>
- Checking & savings account balances<br>
- Loan duration & amount<br>
- Loan purpose & credit history<br>
- Employment details like job type, duration of employment & percentage of monthly income<br>
- Personal demographics like age, number of dependents & phone usage (yes/no)<br>
- Other details like duration at current residence, type of housing, other credits taken & number of credits and default status<br>  
Each entry represents a unique customer, providing a comprehensive view of their personal, professional, financial status and credit history.<br>

**Project Structure:**<br>
The project is organised into several key components:<br>
- README.md: The current file you are reading giving an overview of the project.<br>
- German_bank.csv: The loan default dataset that is provided. <br>
- code_file.ipynb: This is the python code notebook (Jupyter notebook) that detail the following:<br> 
	1. Library Import: <br>
		-> Setting up your Python environment with necessary libraries.<br>
	2. Data Ingestion: <br>
		-> Loading the dataset into your workspace.<br>
	3. Exploratory Data Analysis (EDA): Assessing data quality and characteristics through: <br>
		-> Overview and statistical summaries.<br>
   		-> Null value checks.<br>
   		-> Analysis of class balance.<br>
   		-> Correlation between features through visualisation plots like heatmap & pair plot for multicollinearity & correlation insights.<br>
   		-> Histograms for distribution insights.<br>
   		-> Outlier Analysis.<br>
	4. Data Preprocessing:<br>
   		-> Encoding categorical variables.<br>
   		-> Scaling numerical data to standardise features.<br>
	5. ML Model Building and Optimization:<br>
   		-> Splitting data into training and testing sets.<br>
   		-> Initial model fitting with basic parametric and tree-based models, including cross-validation.<br>
   		-> Hyper-parameter tuning of the most promising models.<br>
   		-> Feature importance analysis to refine model inputs.<br>
   		-> Re-evaluation using only the important features (a reduced feature set).<br>
   		-> Combining best individual models into an ensemble for improved performance.<br>
	6. ML Model Recommendation: <br>
		-> Analysing and comparing model performances to choose the best model for deployment.<br>
- final_report.pdf: Final Report in PDF format with Introduction, Methods and Materials, Results, Discussion & Conclusion.<br>


**Installation:**<br>
To set up the project environment and install the necessary library packages, run the following command in your terminal: <br>

```pip install pandas numpy matplotlib seaborn scikit-learn``` <br>

It is recommended to use a virtual environment. <br>

**Usage:**<br>
Ensure that German_bank.csv and Final Project - Sundar Ram Subramanian.ipynb are in the same directory.<br>
The Jupyter Notebook is optimised to work in any Notebook IDE after installation of the required packages.

