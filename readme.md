# Prosper Loan Data Exploration

## Dataset

The data set covers the time period 2005 to 2014, the first 9 years of the business. loan, including loan amount, borrower rate (or interest rate),current loan status, borrower income, and many others.It contains 113,937 observations of 81 variables.
I chose to explore 11 variables in this dataset:
- Loan origination date: The date the loan originated.
- Loan original amount: The origination amount of the loan.
- Term: The length of the loan expressed in months.
- Loan status: The current status of the loan: Cancelled, Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue.
- Borrower monthly income: The monthly income the borrower stated at the time the listing was created.
- Credit score: The value representing the range of the borrower’s credit score as provided by a consumer credit rating agency. Only lower and upper limits provided.
- Debt to income ratio: The debt to income ratio of the borrower at the time the credit profile was pulled.
- Is borrower homeowner: A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.
- Delinquencies in the last 7 years: Number of delinquencies in the past 7 years at the time the credit profile was pulled.
- EmploymentStatus: The employment status of the borrower at the time they posted the listing.


## Summary of Findings

The multivariate exploration here showed that there indeed is a negative effect of increased credit score, level of employment, DTI ratio, and repayment history on the loan interest rate. The people who are not employed having a higher interest rate and DTI ratio than the people who have jobs. Furthermore, monthly income and debt to income ratio explain some of the variations in loan delinquency status.

Looking back on the point plots, the borrowers who have a part-time job have the lowest loan interest rate which is a little bit absurd. In the future, I will use more variables in this dataset to dig into the reason.


## Key Insights for Presentation

For the presentation, I focus on the determinants of interest rate
and trying to find out what factor affects the borrower’s interest rate. I start by introducing the interest rate, credit score, loan amount, debt to income ratio variables, and their distribution plots.

Afterward, I introduce each of the categorical variables such as loan status and employment status. To start, I use the scatter plots of interest rate and credit score across employment status and loan status. second, I did a deeper analysis by using boxplot to determent if employment status and cat loan status can explain the variation in interest rate.
