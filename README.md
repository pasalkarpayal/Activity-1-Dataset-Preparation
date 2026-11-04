# Activity-1-Dataset-Preparation

1. Objective

To inspect, clean, analyze and prepare a dataset for future machine learning applications using Python.

2. Dataset Information

Dataset Name: Titanic Dataset

Source: Data Science Dojo – GitHub

File Name: titanic.csv

Total Records: 891

Total Columns: 12

File Format: CSV

Dataset Source Link: https://github.com/datasciencedojo/datasets/blob/master/titanic.csv

3. Technologies Used

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

4. Dataset Description

The Titanic dataset contains information about passengers aboard the Titanic ship.

Important features include:

PassengerId

Survived

Pclass

Sex

Age

SibSp

Parch

Fare

Embarked

Cabin

5. Data Preparation Steps

Dataset selection and loading.

Dataset inspection and exploration.

Identification of numerical and categorical features.

Descriptive statistical analysis.

Missing-value identification.

Missing-value handling using median and mode imputation.

Duplicate checking and data consistency.

Exploratory Data Analysis (EDA).

Categorical feature encoding using One-Hot Encoding.

Numerical feature scaling using StandardScaler.

Saving and verifying the prepared dataset.

6. Missing Value Handling

Age: Missing values replaced using median.

Embarked: Missing values replaced using mode.

Cabin: Removed due to a high percentage of missing values.

7. Exploratory Data Analysis

The following visualizations were created:

Age Distribution Histogram.

Passenger Survival Count Bar Chart.

Passenger Fare Box Plot.

8. Data Encoding and Scaling

One-Hot Encoding was applied to Sex and Embarked.

StandardScaler was used to standardize numerical features.

PassengerId and other unnecessary identifier/text columns were excluded from the prepared dataset.

9. Output Files

Activity_1_Dataset_Preparation.ipynb – Completed Google Colab notebook.

titanic.csv – Original dataset.

Titanic_Prepared.csv – Cleaned and prepared dataset.

10. Conclusion

The Titanic dataset was successfully inspected, cleaned and prepared for future machine learning applications. Missing values were handled using suitable imputation techniques, duplicate records and inconsistent categories were checked, and exploratory data analysis was performed.

Categorical features were converted into numerical representations using One-Hot Encoding, and numerical features were standardized using StandardScaler.

Finally, the prepared dataset was verified and saved as a separate CSV file without modifying the original dataset.

This activity demonstrated the importance of data cleaning, exploratory data analysis, encoding and feature scaling in the machine learning workflow.
