# Apexcare-general-hospital-Exploratory Data Analysis(EDA)
Exploratory Data Analysis (EDA) of Patient Admissions at ApexCare General Hospital

## Project Overview

ApexCare General Hospital generates large volumes of patient data daily, including admission records, billing information, and clinical outcomes. To support data driven decision-making, it is essential to analyze patterns, identify trends, and uncover insights that can improve operational efficiency and patient care.
This project performs an Exploratory Data Analysis (EDA) on a synthetic healthcare dataset that mirrors real-world hospital records. Using Python and data analysis libraries, we explore:
	•	Patient demographics
	•	Admission types
	•	Medical conditions
	•	Billing patterns
	•	Insurance provider trends

##Exploratory Questions
This analysis answers the following key questions:
	1.	How many patients were admitted under Emergency admission type?
	2.	How many patients had Urgent admissions?
	3.	What is the distribution of patients’ ages?
	4.	What does the billing amount distribution look like?
	5.	How many unique medical conditions are recorded?
	6.	What are the most common medical conditions?

##Dataset Description
The dataset contains hospital patient records with the following features:
	•	Age
	•	Gender
	•	Blood Type
	•	Medical Condition
	•	Date of Admission
	•	Insurance Provider
	•	Billing Amount
	•	Room Number
	•	Admission Type

##Data Cleaning Process
The following steps were performed using Python in VS Code:
	1.	Imported the dataset into VS Code
	2.	Imported required libraries: pandas, numpy, seaborn, and matplotlib
	3.	Inspected the dataset using:
	•	.head() (first 5 rows)
	•	.tail() (last 5 rows)
	4.	Checked dataset shape (number of rows and columns)
	5.	Used .describe() for statistical summary
	6.	Converted Date of Admission from object type to datetime
	7.	Checked and handled duplicate records
	8.	Identified negative values in length of stay and replaced them with NaN

## Analysis Steps
	1.	Created a Length of Stay column to calculate the number of days each patient spent in the hospital.
	2.	Identified and handled invalid negative values.
	3.	Counted each Admission Type and visualized results using Seaborn and Matplotlib.
	4.	Performed Age Distribution Analysis using histograms.
	5.	Analyzed Billing Amount Distribution using histograms.
	6.	Added KDE (Kernel Density Estimation) to visualize billing density patterns.
	7.	Counted medical conditions and visualized their frequency using bar charts.
	8.	Calculated the average billing amount per insurance provider.

##Visualizations

The following visualizations were created using Python:
	•Box Plot (for billing spread and outliers)
	•Bar Chart (Admission types & medical conditions)
	•Histogram (Age & Billing distributions)
	•KDE Curve (Billing density analysis)


##Key Insights
	•	Emergency admissions accounted for a significant proportion of total hospital entries.
	•	Certain medical conditions were more prevalent than others, indicating potential seasonal or demographic patterns.
	•	Billing amounts showed a right-skewed distribution, suggesting the presence of high-cost outliers.
	•	Some insurance providers were associated with higher average billing amounts.
	•	Age distribution revealed concentration within specific age groups, which may influence hospital resource planning.
	•	Length of stay varied significantly, with some extreme values indicating potential data entry issues or complex cases.

##Tools Used
	•	Python
	•	VS Code
	•	Pandas
	•	NumPy
	•	Seaborn
	•	Matplotlib

##Project Goal

The goal of this project is to demonstrate practical data cleaning, exploratory analysis, and visualization skills using Python transforming raw healthcare data into meaningful insights that can support informed decision-making.
##Author
Name:Khairat Hakeem
Role:Data Analyst
