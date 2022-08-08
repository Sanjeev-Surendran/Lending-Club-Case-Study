# Lending Club Case Study
A case study to solve a business problem using Exploratory Data Analysis (EDA).
* Comprehend the given data set and perform EDA to solve the business objective.
* Present the EDA analysis and recommendations to Client to avoid risk in doing business.

## Table of Contents
* [General Info](#general-information)
* [Project Contents](#project-contents)
* [Conclusion](#conclusion)
* [Software and Library Versions](#software-and-library-versions)
* [Acknowledgements](#acknowledgements)

### General Information
Lending Club is a Consumer Finance Company which specialises in lending loans to customers. The company requires to approve and reject loan applications, to minimize the risk of business loss and financial loss.
* **Business loss** happens when a loan is rejected to a applicant, who is likely to repay the loan amount.
* **Financial loss** happens when a loan is approved to a applicant, who is likely not to repay the loan amount.

##### Business Objective
Analyze and Perform Exploratory Data Analysis (EDA) on the given data set, identify the driving factors that indicates why the applicant defaulted.

##### Business Solution
Present a solution using driving factors, which can predict whether a new applicant is likely to default or not. Lending Club will utilize this knowledge for its portfolio and risk assessments.

##### Data Set Brief Information
The data set is from Lending Club, that contains information about past loan applicants and whether they defaulted or not. The data set doesn't contain any transactional history about loan rejection.
The data set contains history of approved loans between years 2007-2011 and it contains loan status of all applications. There are 3 loan statuses available:
* **Fully paid** - Applicant has fully paid the loan.
* **Current** - Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed.
* **Charged-off** - Applicant has not paid the instalments in due time for a long period of time, i.e. applicant has defaulted on the loan.

A data dictionary is provided along with the data set to understand various terms and variables used in loan risk assessment.

### Project Contents
* **Data_Dictionary.xlsx** - Data Dictionary
* **Lending Club Case Study.ipynb** - Jupyter Notebook
* **Lending Club Case Study.pdf** - Presentation on Business Solution
* **loan.csv** - Data Set
* **README.md** - Readme file


### Conclusion
Any business analytics problem can be solved using **CR**oss **I**ndustry **S**tandard **P**rocess for **D**ata **M**ining (CRISP-DM) model.
Data set was analyzed and prepared for EDA. Univariate and Bivariate analysis were done on data set to understand the relationship between variables and to identify the driving factors in identify why applicants defaulted.
##### Recommendation
**Based on Demography of Applicant**
* Applicants who previously defaulted will default again.
* Extra scrutiny is required for Applicants belonging States NV and CA, since they have high tendency to default.
* If Annual Income is more, there is very less chance to default.
* Extra scrutiny is required if Applicants have employment length less than 1 year or no job history.
* Higher chance of default if DTI and Interest rate is very high.

**Based on Loan Characteristics**
* Loans with high interest rate have high tendency to default.
* High tendency to default, if the loan tenure is 60 months.
* Extra scrutiny is required if the purpose of loan applied is for small business.
* More defaulting can be expected when loans applied are high and it is during holiday (winter).


### Software and Library Versions
* ![Jupyter Notebook](https://img.shields.io/static/v1?label=Jupyter%20Notebook&message=4.9.2&color=blue&labelColor=grey)

* ![NumPy](https://img.shields.io/static/v1?label=numpy&message=1.21.5&color=blue&labelColor=grey)

* ![Pandas](https://img.shields.io/static/v1?label=pandas&message=1.4.2&color=blue&labelColor=grey)

* ![matplotlib](https://img.shields.io/static/v1?label=matplotlib&message=3.5.1&color=blue&labelColor=grey)

* ![seaborn](https://img.shields.io/static/v1?label=seaborn&message=0.11.2&color=blue&labelColor=grey)

* ![re](https://img.shields.io/static/v1?label=re&message=2.2.1&color=blue&labelColor=grey)


### Acknowledgements
This case study is an assignment, done as part of [Upgrad](https://www.upgrad.com/ ) - **Master of Science in Machine Learning & Artificial Intelligence** programme.


### Contact
Created by [Sanjeev Surendran](https://github.com/Sanjeev-Surendran)


<!-- ## License -->
<!-- This project is not a open source and sharing the project files is prohibited. -->