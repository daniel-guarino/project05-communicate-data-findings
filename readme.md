# Dataset: Loan Data from Prosper
## by Daniel Guarino


## Dataset

> - This analysis was made in a reduced dataset (12 variables out 81) about personal loans, where we have important attributes to describe a loan status like the Amount of money asked, the Term (in months), the Interest Rates, the Rating Scores among others attributes. This data was provided by Prosper.


## Summary of Findings

### Univariate Exploration

- Three different time terms: 1- 36 months (most common), 2- 60 months, 3- 12 months (less common). Further we should analyse together other variables like Borrower Rating or Loan Original Amount, by itself this variable does not tell us too much things.

- Half of the Prosper's loans have the status **Current** (i.e: A loan when one or more payments have been completed and no payments are past due. It also means that this loan still has one or more scheduled future payments.)
One third are already completed and 16.77% have had some trouble. These 16.77% could be compared to other companies of the same field to know if Prosper has a high ratio of troubled loans. 

- The interest rate mean is 19.28%. This variable is better when analyzed with another variable as can be seen in the conclusion of the multivariate exploration. 

- The most common reason for a loan is Debt Consolidations. According to Prosper's Wikipedia page this is a "form of debt refinancing that entails taking out one loan to pay off many others", which mean these loans were taken in order to resolve another debts.

- California is the state with most loans (more than the double of the second, third and fourth states with more loans) followed by Texas, New York, Florida and Illinois. Focus more on the loans made in California.

### Bivariate Exploration

- Taking some insights from the univariate exploration we learnt most of loans were made by employed people. Here we see that people with income range between USD 25k - USD 50K (the most common) pay the average interest, while unemployed pay much more than this. People with income range USD 50k - USD 75k (the second most common) pay a liitle bit less. Those who earn more than USS100k/year are paying the smaller rates.

- Debt consolidation is the most common category as seen in the univariate exploration. The higher interest taxes are paid by people in the third quartile of categories like Household Expenses and Cosmetic Procedures. They pay the higher interest taxes.

### Multivariate Exploration

- Loan Amounts higher than USD 25,5k are always made by people with the highest income range USD 100k.
- Most of unemployed people ask a 60 month loan term.
- The most common income range people (USD 25k to USD 50k) ask for a 12 loan term.
- People with no income asks more for a 36 month loan term.


## Key Insights for Presentation

- Three different time terms: 1- 36 months (most common), 2- 60 months, 3- 12 months (less common). Further we should analyse together other variables like Borrower Rating or Loan Original Amount, by itself this variable does not tell us too much things.
- The most common reason for a loan is Debt Consolidations. According to Prosper's Wikipedia page this is a "form of debt refinancing that entails taking out one loan to pay off many others", which mean these loans were taken in order to resolve another debts.
- Loan Amounts higher than USD 25,5k are always made by people with the highest income range USD 100k.
- Most of unemployed people ask a 60 month loan term.
- The most common income range people (USD 25k to USD 50k) ask for a 12 loan term.
- People with no income asks more for a 36 month loan term.