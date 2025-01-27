# Project Name: Lending Club CaseStudy 

## Table of Contents
* [Background](#background)
* [Technologies Used](#technologies-used)
* [Conclusions](#conculsions)
* [Acknowledgements](#acknowledgements)
* [Collaborators](#collaborators)

### Background:
#### Business Understanding
A consumer finance company, which specialises in lending various types of loans to urban customers, when receives a loan application, has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

#### Business Objective
Company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment

The data given to us contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

**Dataset** used is - "loan.csv" and "Data_Dictionary.xlsx"


### Technologies Used:
* Python - version 3.12.4
* Numpy - version 1.26.4
* Pandas - version 2.2.2
* Seaborn - version 0.13.2
* Matplotlib - version 3.8.4
* Plotly - version 5.22.0

### Conculsions:
The driving factors that impact defaulting of loan are
* Annual Income
* Purpose
* DTI
* Verification Status
* Grade
* State

#### Other Considerations:

* More scrutiny while lending money to states like CA, FL, NY & TX
* Advisable to lend money after doing Source Verification
* Careful with Borrowers having high DTI value
* Scrutinize Borrowers who are having annual income in the range of 25K to 100K and who have 10+ years or less than 1 years of employments


### Acknowledgements:
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.
Special thanks to the team for providing the resources and support for this case study.

This project was based on [Advance EDA](https://www.youtube.com/watch?v=bNY3Xaxww7g&t=1771s), [Exploratory Data Analysis in Python](https://www.udemy.com/course/exploratory-data-analysis-in-python)


### Collaborators:
 [Girish Kumar](https://github.com/ga898) and  [Ganesh Peri](https://github.com/)
