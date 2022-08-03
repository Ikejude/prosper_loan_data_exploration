# Explorating Loan Data From Prosper
## By Madu Ikechukwu


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 

### Data Wrangling:
The following are the data wrangling processes carried out on the dataset.

1. Data cleaning for quality issues:
The data set was cleaned for quality issues by
a) Making a copy of the original dataset.
b) Removing rows with null values
c) Removing rows with duplicates
d) Changing datatypes of some variables to the right data type
e) Data transformation for few variables to make them normally distributed.
f) Removing columns that are not needed for further data exploration
g) Saving the cleaned dataset.

The following variables were selected after data cleaning for further analysis:
(ListingNumber, Term, LoanStatus, BorrowerAPR, BorrowerRate, LenderYield, ProsperScore, ListingCategory,BorrowerState, Occupation, EmploymentStatus, AmountDelinquent, TotalProsperLoans, TotalProsperPaymentsBilled, OnTimeProsperPayments, ProsperPaymentsLessThanOneMonthLate, ProsperPaymentsOneMonthPlusLate, ProsperPrincipalBorrowed, LoanOriginalAmount, LoanOriginationDate)

## Summary of Findings

In summary, having followed the outlined steps as provided in the introduction of this project, the following conclusions are drawn:

1. There was a steady fall in the lender yield (interest rate of the borrower) in subsequent years immediately after it attained it highest point in the second year, 2010.

2. Although with a higher loan risk, the lender tends to have high interest rate for loans that default. Loans that exceed 120 days of repayment have high risk and can become chargedoff loans to the lender.

3. More loans are taken by the employed section of the borrower than any other. 

4. There is high risk for loans with high lender yield.

5. NM state had borrowers with the highest loan principal taken, while SD state had borrowers taking the least principal loan amount.

6. The employed borrowers have more loans that have defaulted than other selected employment-status borrowers. The employed and full-time borrowers have the highest number of completed loans.

7. The larger the amount of principal borrowed, the less value is the lender yield (interest rate). While loans that are going bad or that have high risk lead to high lender yield, it seems to appear that loans with low principal amount tend to turn bad for the borrower.

8. The earlier the loans repaid, the more loans the lender is willing to give out as shown in the strong positive relationship betweem OnTimeProsperPayments and TotalProsperLoans.

9. Changes in the amount of loans delinquents can not be determined from other numeric variables as selected for this project.

10. BorrowerAPR, BorrowerRate and LenderYield all have the same effect as the interest rate as they have very strong positive correlation.

## Conclusion

The conclusions drawn from the analysis of the data set are given below :
* More loans are taken by borrowers that are employed.
* Loans with high lender yield have high risk.
* Employed borrowers have more loans that defaulted.
* Loans with large capital amount have low interest rate than loans with small capital amount.
* There is high risk for defaulting loans than the ones that are repaid as timely as possible. That is the probability of loans becoming bad is high for those that default. This implies that Prosper score has direct impact on the loan status.
