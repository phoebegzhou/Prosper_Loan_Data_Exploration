# Factors that Affect Loan Status


## Dataset

For this project, I wanted to look at which factors impact loan status. The main focus was on borrower credit score lower range, borrower APR, loan original amounts, available bank card credit, and the Prosper ratings. The data consisted of loan status and attributes of 113937 loan listings. To be consistent and accurate with the timeline fot the investigation, I only retrieved data after July 2009 and removed listings with unrealist monthly salary.

## Summary of Findings

In the exploration, I found that borrower APR and credit score lower range have relatively strong negative correlation. Borrower APR also has negative correlation with loan original amount and available bank card credit. There are relatively strong positive correlation between available bank card credit and credit score lower range. There are some unusual findings for relationship between loan status with the four numeric variables. Past due 91-120 days has lower median APR than other past due days that are smaller. Past due 16-30 days has the second highest median borrower APR following defaulted, higher than that of chargedoff. Surprisingly, past due 91-120 day has the highest median loan amount. Past due 1-15 days has the lowest credit score comparing to defaulted or charged off. The final payment in progress category has the strongest relationship between borrower APR and credit score. The past due >120 days category has the weakest relationship between borrower APR and credit score. 

## Key Insights for Presentation
For the presentation, I focused on the relationships between loan status with borrower credit score lower range, borrower APR, loan original amounts, available bank card credit, and the Prosper ratings. I used scatterplots and boxplots to look at several numeric variables and categorical variables one by one. 
The relationship between borrower APR and credit score is normal, with HR rating having highest APR, and AA rating having the lowest APR. However, HR (high risk) rating actually has higher credit score than rating E, which is the next riskiest rating, and about the same credit score with rating D.
