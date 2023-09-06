# Lending Club Case Study
Lending Club is one of the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

The company wants to understand the driving factors (or driver variables) behind loan default using EDA (Exploratory Data Analysis), i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contacts](#contacts)

## General Information
This project aims to analyze a dataset containing loan-related information to identify key factors that contribute to loan defaults. By conducting Exploratory Data Analysis (EDA) on the dataset, to uncover patterns and insights that can help the company make informed decisions regarding risk assessment and portfolio management.

### Background
In the financial industry, managing loan default risk is of utmost importance for ensuring the stability of lending portfolios and minimizing potential credit losses. To achieve this, it is crucial for financial institutions to identify the driving factors behind loan defaults. Exploring historical loan data through EDA can provide valuable insights into the characteristics and behaviors of defaulting borrowers.

### Business Problem
The primary business problem addressed by this project is to understand the factors that contribute to loan defaults. By identifying the variables that serve as strong indicators of loan default, financial institutions can make more accurate risk assessments and reduce the number of high-risk loans in their portfolio. This knowledge can ultimately lead to a reduction in credit losses and enhanced portfolio management.

### Dataset
The dataset used for this project contains a wide range of loan-related information, including borrower characteristics, loan terms, credit scores, and more. The dataset enables us to examine how various attributes relate to the likelihood of a loan being classified as "Charged Off" or defaulted. The dataset allows us to explore both numerical and categorical variables, providing a comprehensive view of borrower behavior and loan performance.

The columns in the dataset include:

id, member_id, loan_amnt, funded_amnt, funded_amnt_inv, and more (a total of numerous columns).
Notably, the loan_status column categorizes loans as "Charged Off" or in various other states.
By analyzing this dataset, we aim to gain insights into the key drivers of loan defaults, ultimately assisting financial institutions in making well-informed decisions to mitigate risk and optimize their lending strategies.

## Technologies Used
- Python - 3.9.17
- jupyterlab - 3.6.3
- numpy - 1.24.3
- pandas - 2.0.3
- matplotlib - 3.7.1
- seaborn - 0.12.2

## Conclusions
- Rejectable Loans:
1. Loans above 25000 and interest rate more than 15% have higher chance for Charged Off
2. Loans above 30000 and installment above 800 have higher chance for Charged Off
3. Loans applied for 'house' with Interest rate above 15% have higher chance for Charged Off
4. Loans under grade 'G' with Interest rate above 20% have higher chance for Charged Off
5. Applicants on 'Mortgage' home and loan above 13000 have higher chance for Charged Off
- Approvable loans:
6. Loans below 25000, interest rate below 15% and not for 'house'
7. Loans below grade 'G' and interest rate below 20%
8. Loans below 13000 and not under 'Mortgage'

## Acknowledgements
- Dataset from upGrad for Lending Club Case Study
- Based on this tutorial https://www.kaggle.com/code/ab9bhatia/complete-eda-for-loan-analysis

## Contacts
Created by Syed Abdul Rahim [@sarpsl] & Leena Orpe [@leenaorpe] - feel free to contact us!
