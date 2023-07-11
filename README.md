# Data_analytics_Loan_default
Final_project_coding_mentor

Files included:
01 Tableau file visualising the data analysed.
01 CSV file cleaned data. 
01 CSV file before cleaning. 

OVERVIEWS: 
1. About the dataset:
1.1. This is a dataset about lending operation of a bank in India in 2019 (source: Kaggle.com)
1.2. The dataset (after cleaning) includes 45915 rows and 34 columns (25 dimensions and 9 measures)
   
2. How the raw dataset is cleaned:
I used filter function to filter out blank cells. In this case, I am not able to find the correct values for those cells since the dataset comes from a third-party. Therefore, I filtered them out as they just account for less than 6% the number of records.

3. Visualisations and findings:
I used Tableau to create dashboards and stories which demonstrate the bank's operation overviews (lending activities, groups of customers, profits per regions...). They also indicate loan defaults and their effects to the bank.

4. Definitions of key columns in the dataset:
- What Is the Loan-to-Value (LTV) Ratio?
The loan-to-value (LTV) ratio is an assessment of lending risk that financial institutions and other lenders examine before approving a mortgage. Typically, loan assessments with high LTV ratios are considered higher-risk loans. Therefore, if the mortgage is approved, the loan has a higher interest rate.
An LTV ratio is calculated by dividing the amount borrowed by the appraised value of the property, expressed as a percentage. For example, if you buy a home appraised at $100,000 for its appraised value, and make a $10,000 down payment, you will borrow $90,000. This results in an LTV ratio of 90% (i.e., 90,000/100,000).
- Loan Limit cf/ncf
CF loan guarantees approved in Fiscal Year 2021 will receive an 80 percent guarantee. What is the maximum loan amount? The maximum amount of a guaranteed loan is $100 million.
- A loan pre-approval means that a lender has agreed, in principle, to lend you an amount of money towards the purchase of your home but hasn't proceeded to a full or final approval. It allows you to know your maximum available funds so you can narrow your search, negotiate with more certainty, and bid with more confidence if you're going to auction.
- Credit worthiness: I1 is an indication of a good payment history and I9 is an indication of a poor payment history. • “Charged-Off.” This means the creditor has acknowledged your debt as a loss in its financial records.
- What is Open Credit? 
Open credit is a pre-approved loan between a lender and a borrower. It allows the borrower to make repeated withdrawals up to a certain limit and then make subsequent repayments before the payments become due.
Borrowers prefer open-end credit because it gives them greater control over the amount they can borrow and the repayment period. Interest is only charged on the credit that the borrower has used, and the borrower does not incur costs on the unused credit.
- The net interest rate spread is the difference between what a bank pays on deposits and what it charges on loans (like profit margin).
- An upfront fee is a common fee charged by lenders when you apply for a loan. It might also be called an ‘application’ fee or ‘establishment’ fee. 
- Negative amortization means that even when you pay, the amount you owe will still go up because you are not paying enough to cover the interest. 
- A lump-sum payment is a monetary sum paid in one single payment instead of allocated into instalments.
- The debt-to-income (DTI) ratio is the percentage of your gross monthly income that goes to paying your monthly debt payments.

5. How to calculate the bank's profits/losses within a year?
Profits = Sum(Loan amount * Interest rate spread + Upfront charges)
Losses = Sum(Loan default * Interest rate spread)
