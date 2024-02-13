# Financial Loan Analysis
The core of this analysis addresses pivotal questions impacting the financial dimensions of lending on the Prosper platform. It explores the determinants of borrower APRs and interest rates, the relationship between loan amounts and their terms, and the factors influencing loan outcomes. Employing a mix of quantitative analysis and data visualization, Financial Loan Analysis reveals the complex interplay between borrower profiles and loan performance.

## Dataset

The dataset consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. 

## Summary of Findings

In the exploration part, I found out that the borrower APR is negatively correlated with original loan amount. At different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount. The borrower APR also decreases with the increasingly better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. Interestingly, the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings are increased from HR to A or better. This is may because people with A or AA ratings tend to borrow more money, increasting APR could prevent them borrow even more and maximize the profit. But people with lower ratings tend to borrow less money, decreasing APR could encourage them to borrow more. I also found that the borrower APR decrease with the increase of borrow term for people with HR-C raings. But for people with B-AA ratings, the APR increase with the increase of borrow term.

Outside of the main variables of interest, I found that the loan amount is positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income could loan more money. The loan amount is also increased with the increase of loan term. I also found that borrowers with better ratings have larger monthly income and loan amount. Employed, self-employed and full time borrowers have more monthly income and loan amount than part-time, retired and not employed borrowers. There is a interaction between categorical term and Prosper rating features. Proportionally, there are more 60 month loans on B and C ratings. There is only 36 months loans for HR rating borrowers. For loan amount, there is a interaction between term and rating. With better Prosper rating, the loan amount of all three terms increases, the increase amplitude of loan amount between terms also becomes larger.


## Key Insights for Presentation

The correlation between BorrowerAPR and loan amount is moderately negative correlection. The higher the loan amount fee, the Lower the BorrowerAPR and the lower the loan amount fee. At different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount. Overall, the borrower APR decrease with increase of loan amount

The majority of Prosper borrowers are employed, and the majority of these borrowers have low ratings on Prosper.

Borrowers with lower scores typically have a better rate when asking for a loan for 60 months as opposed to 12 and 36 months, while borrowers with higher scores typically have a higher rate when applying for a loan for 60 months as opposed to 12 and 36 months.
