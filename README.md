# Communicate Data Findings
## by Ayodeji Arowolo


## Dataset

> The data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset primarily consists of data on the borrower's and the loan performance information.


## Summary of Findings

> In this project, I investigated and sought insights to the features affecting borrower rate and loan amount.

> I first performed the following wrangling steps to make the data easy to work with.
1. Decide on the columns that I will use for the analysis.
2. Subset the columns from the original data that I will use.
3. Drop any duplicated rows
4. Subset for rows with a ProsperRating value 
5. Fill missing values
6. Change Datatypes 

> Thereon, I performed exploratory data analysis on the dataset and found out the following
1. The loan applied and granted increased between 2009 and 2013, after which it declined in 2014
2. Janaury had the highest loans, while April had the least
3. The 31st day has the lowest loans, this could be attributed to the fact that not all months have 31 days
4. The highest borrower APR was around 0.43, loans were not given higher than that rate. The distribution of APR is bimodal with a high peak around 0.35
5. 4000,10000 and 15000 dollars were the most requested and granted loan amounts
6. There was a peak for the debt to income ratio at around 0.3. This means that a good portion of the loan was distributed to people who took a loan worth 33.3% of their income. This is actually a financial best practice, as one shouldn't overburden themselves with a lot of debt. Also, the frequencies after the ratio of 0.3 reduced, as it will be more difficult to keep up with repaying such loans.
7. There were significantly more 36 month loans than others
8.Employment affects loans, the better the borrower's employment, the higher the likelihood he could get a loan
9.BorrowerAPR and the loan amount have a negative correlation of -0.426. This is in line with my experience in the financial industry, as the higher the loan amount, the lower the interest rates. The loan amount has a positive correlation with stated income. 
10. Students had access to the least loans, which could be due to their reduced stated income.
11. The higher the term, the higher the loan amount that can be availed to a borrower.
12. Borrowing rates have been reducing year on year since 2011
13. Employed borrowers with the highest rating almost enjoyed fixed rates regardless of the loan amount and they could be charged higher rates with higher loan amounts.


## Key Insights for Presentation


> I focused on the influence of some variables on interest rate and loan.
> With a scatter plot, I was able to show that the loan amount generally varies inversely with borrowing APR

> I presented that borrowers with higher ratings enjoyed relatively lower borrowing rates. 


"# ProsperLoanDataAnalysis" 
