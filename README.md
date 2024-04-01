Easy Visa Prediction
This repository contains code for predicting visa approval using the Easy Visa dataset. The dataset contains information about visa applications including various features such as continent, education of employee, job experience, prevailing wage, etc.

Dataset Information
The dataset contains the following columns:

case_id: Unique identifier for each case
continent: Continent of the applicant
education_of_employee: Education level of the employee
has_job_experience: Whether the employee has job experience (Y/N)
requires_job_training: Whether job training is required (Y/N)
no_of_employees: Number of employees
yr_of_estab: Year of establishment
region_of_employment: Region of employment
prevailing_wage: Prevailing wage
unit_of_wage: Unit of wage (Hour, Year, Week, Month)
full_time_position: Whether the position is full-time (Y/N)
case_status: Visa approval status (Certified/Denied)
Exploratory Data Analysis
The notebook Easy_Visa_Prediction.ipynb contains the following sections:

Importing Libraries: Importing necessary libraries for data analysis and visualization.
Loading the Dataset: Loading the Easy Visa dataset into a Pandas DataFrame.
Dataset Shape: Displaying the shape of the dataset.
Showing All Columns: Displaying all the columns in the dataset.
Showing DataTypes: Displaying the data types of columns.
Dataset Information: Displaying information about the dataset including data types, non-null counts, and memory usage.
Checking Null Values: Checking for null values in the dataset.
Exploratory Data Analysis (EDA): Analyzing the dataset to gain insights:
Finding Numerical and Categorical Columns
Properties of Count Data on Categorical Columns
Univariate Analysis (Numerical and Categorical Features)
Multivariate Analysis (Discrete and Continuous Features, Correlation, Heatmap)
Chi-square Test for Feature Selection
Visualizing Outliers and Boxplots
Visualizing Target Features
Analyzing Impact of Continent, Education, Job Experience, Job Training, Number of Employees, Wage, and Region of Employment on Visa Status
Conclusion
The analysis provides insights into various factors affecting visa approval, including continent, education, job experience, job training, number of employees, wage, and region of employment. This information can be valuable for predicting visa approval outcomes.

Feel free to explore the notebook for detailed analysis and insights!
