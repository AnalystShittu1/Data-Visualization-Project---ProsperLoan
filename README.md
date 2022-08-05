# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The data consists of information regarding 113,917 prosper loans,, including borrower rate, borrower apr, prosper rating, loan amount, emploment status and other loan performance and borrower information qualities. The dataset can be found in Udacity webhost [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000),
 

## Summary of Findings

> In the exploration, I found that there was a strong relationship between the borrower's cost (APR), borrower rate and prosper rating. while the borrower APR increases with increasing borrower rate i.e possitively correlated, borrower cost decreases with increasingly better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. Also, APR is negatively correlated with original loan amount. At different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount.  Interestingly, the borrowers with better prosper ratings took higher loan values and pay less cost (APR). This is may be a form of insentive for better rated customers to borrow more money as decreasing APR could motivate them and the business inturn maximize profit. in the same vein, for borrowers with lower raings i.e HR-C , APR decreases with the increase of repayment term. However, for borrowers with Higher ratings i.e B-AA, the APR increase with the increase of borrow term.

> Outside of the main variables of interest, I looked at the relationship between employment status, loan amount and repayment term. I found an interesting interaction among the variables. Larger loan amount are granted to mostly employed borrowers possibly due to their verifiable means of repayment. another interesting outcome is that loan amount also increases with the increase of loan term. I also unemployed, retired and part-time worker borrowers majorly repay over a longer term between 36-60 despite taking lesser loan amount. 

## Key Insights for Presentation

> For the presentation, I focus on just the features that could affect the borrower's cost (APR), which are borrwer rate, original loan amount, term and Prosper rating. I start by introducing and showing the pattern in APR  and loan amount variable distribution. Then, plot the regression scatterplot of APR against the numerical variables to generate relationship insights. 

> Afterwards, I present each of the categorical variables (like term, employment status,ocuppation) one by one and subsequently checked thier relationship with the variable of interest and other desired variables. Overall, i am looking for pattern of borrowers information that further explains overall cost trend.
