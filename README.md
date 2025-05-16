**Bank Loan Data Analysis**
This repository contains a Python project for exploratory data analysis (EDA) on a bank loan dataset. The analysis is performed in a Jupyter Notebook using pandas, seaborn, and matplotlib.

**Project Overview**

This project explores the relationships between various customer features and personal loan approval status in a bank's customer dataset. The analysis includes:

**Data cleaning and inspection**

Visualization of feature distributions

Correlation analysis

Insights into factors influencing loan approval


**Dataset**

The dataset (bankloan.csv) includes the following columns:

ID: Customer ID

Age: Age of the customer

Experience: Years of professional experience

Income: Annual income (in $000s)

ZIP.Code: ZIP code of residence

Family: Family size

CCAvg: Average credit card spending (in $000s)

Education: Education level (1 = Undergrad, 2 = Graduate, 3 = Advanced/Professional)

Mortgage: Value of house mortgage (in $000s)

Personal.Loan: Whether the customer accepted a personal loan (1 = Yes, 0 = No)

Securities.Account: Has a securities account (1 = Yes, 0 = No)

CD.Account: Has a certificate of deposit account (1 = Yes, 0 = No)

Online: Uses online banking (1 = Yes, 0 = No)

CreditCard: Has a credit card issued by the bank (1 = Yes, 0 = No)



**Key Analyses**

Missing Value Check:
Checked for missing values in all columns.

Correlation Heatmap:
Visualized correlations between numerical features to identify relationships.

Age Distribution:
Plotted the distribution of customer ages.

Loan Approval by Education Level:
Compared loan approval rates across different education levels.

Loan Approval by Online Banking Usage:
Explored how online banking usage relates to loan approval rates.


**How to Run**

Clone this repository.

Ensure you have Python 3.12+ installed.

**Install dependencies:**

pip install pandas seaborn matplotlib
Place the bankloan.csv file in the project directory.

Open python-sem-project-1.ipynb in Jupyter Notebook or JupyterLab.

Run the notebook cells sequentially.

Sample Visualizations

Correlation heatmap of all features

Age distribution histogram

Count plots for loan approval by education and online banking usage

Dependencies

pandas

seaborn

matplotlib


**Author**

Abhimanyu Kotari


**License**

This project is for educational purposes. Please check individual data and code licenses before reuse.

Acknowledgements

Dataset source: it is preview

Inspired by data science coursework and practical analytics projects

Feel free to fork, modify, and contribute!
