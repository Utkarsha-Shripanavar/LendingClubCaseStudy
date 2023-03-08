# Lending Club Case Study
>The objective of this project is to analyse loan dataset and figure out the variables leading to defaulters.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
For a consumer finance company that receives lot of loan application,the company has to make a decision for loan approval based on the applicant’s profile.

Two types of risks are associated with the bank’s decision:
   - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
   - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
     
According to business when a person applies for a loan,there are two types of decisions that could be taken by the company:

- Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
     - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
     - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. 
       These candidates are not labelled as 'defaulted'.
     - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, 
  there is no   transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
  
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access    lower interest rate loans through a fast online interface. 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
So if we are able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 

Identification of such applicants using EDA is the aim of this case study.
We can achive this by understanding driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment. 

The data set used to analyse, contains information about past loan applicants and whether they ‘defaulted’ or not.
The aim is to identify patterns which indicate if a person is likely to default
Also to decide actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc
  
Using concepts of EDA to understand how consumer attributes and loan attributes influence the tendency of default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- By looking at the data set we understand that Loan Status is our target variable, 
 
 Upon doing the bivariate analysis over the categorical variables with respect to target variable loan_status it can be concluded that :- 
   - Borrower who choose term of 60 months tend to have 30% more chances of default then people with loan term of 30 months
   - Borrower who take loan grade is of F and G tends to have higher defaulting chances of 30% then compared to other grades 
   - Borrower who take loan Sub grade F5 have 50% chances of defaulting
   - Borrower who apply for the loan with the purpose of 'small business' have 30% more chances of defaulting then other purposes.
   
  Upon doing a bivariate analysis on numerical variables with respect to target variable loan_status it can be concluded that :-
   - Borrower whose loam amount is more, have higher chances of being defaulted
   - Borrower who has taken loan with higher interest rate have higer chances of being defaulted
   - Borrower who have more number of enquires in the last 6 months, have more chances of being defaulted
   - If the amount of credit the borrower is using relative to all available revolving credit is high then there are higher chances of being defaulted


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python Jupyter version 3
GitHub


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by EDA module
- This project was based on learnings acquired in this tutorial https://learn.upgrad.com/course/4476/segment/32128/190535/586561/3000753


## Contact
Created by [@Utkarsha-Shripanavar,@KhyatiDesai09] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available on git repository called LendingClubCaseStudy

<!-- You don't have to include all sections - just the one's relevant to your project -->
