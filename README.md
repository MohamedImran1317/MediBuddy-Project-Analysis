Project Title: MediBuddy Insurance Analysis – EDA Project

Project Overview:
This project focuses on Exploratory Data Analysis of a MediBuddy insurance dataset. The aim is to understand how demographic and health-related factors influence medical insurance claim amounts and to derive insights beneficial for insurance policy decisions.

Problem Statement:
To determine whether variables such as age, BMI, smoker status, gender, dependents, and geographical region have an impact on the claim amounts paid by the insurance company.

Business Objective:
The objective is to support data-driven insurance decisions by improving risk understanding, pricing strategies, underwriting, and customer segmentation. This includes identifying important health indicators and eliminating non-influential attributes.

Dataset Information:
Two datasets were provided:

Dataset 1: Age, Sex, BMI, Charges

Dataset 2: Children, Smoker, Region

Both datasets were merged using the common Policy Number.
Final dataset after merging:

Rows: 1338

Columns: 8

No missing values

No duplicate values

Variable Description:
Policy no. – Unique policy identifier
age – Age of insured individual
sex – Gender of the policy holder
bmi – Body Mass Index indicating obesity and health risk
children – Number of dependents
smoker – Indicates smoking habit
region – Geographic location of the customer
charges in INR – Medical claim amount

Tools & Technologies Used:
Python
Pandas
NumPy
Jupyter Notebook

EDA Steps Performed:
Data loading
Data merging
Data cleaning
Data wrangling
Statistical summary
Exploratory data analysis
Business interpretation
Conclusion and recommendations

Insights Summary Based on 8 Questions:

Gender does not significantly influence claim amounts.

Average claim amount is around ₹13,000.

Region does not have significant impact on claims.

Number of dependents does not influence claims.

Higher BMI is associated with higher claim values.

Smokers claim significantly more than non-smokers.

Age correlates positively with claim amounts.

Health-based discounts can be offered based on BMI and smoker status.

Business Impact:
The insights help improve underwriting, enhance pricing strategies, identify risk groups, and support wellness incentive programs. This reduces long-term claim costs and enhances insurer-customer relationships.

Conclusion:
The project identified age, BMI, and smoking status as critical factors influencing insurance claim amounts. Variables like gender, region, and dependents do not show meaningful influence. These insights support more accurate and fair insurance policy decisions.

Future Scope:
Machine learning models can be used to predict claim amounts. Additional health variables and multi-year datasets can improve analysis. Visualization dashboards can be developed for interactive insights.

Author Details:
Name: Mohamed Imran M
Role: Data Analytics Intern
Technologies Used: Python, Pandas, Jupyter Notebook

Repository Contains:
Notebook
EDA analysis
Insights report
Supporting files
