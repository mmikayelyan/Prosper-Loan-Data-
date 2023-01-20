# Prosper Loan Dataset Exploration
## by Manuk Mikayelyan

## Dataset

> The [dataset](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000) used in this project contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. More detailed information about the dataset's variables can be found in this data [dictionary](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000).

## Summary of Findings

> In the exploration, we selected 13 features that we supposed to have more influence on loan defaulting. We explored the main variable of interest `Loan Status` and the selected features step by step by cleaning the data and building univariate, bivariate, multivariate visualizations. At the end of the exploration, we identified that the borrowers who satisfy the following conditions are more likely not to defult and complete their loans:
   - Employed
   - Dept to Income ratio <= 0.2
   - Prosper Rating between D and A
   - Recommedations >=10
   
> Outside of the main variables of interest, we identified relationship amoung Annual Percentage Rate (APR) for the loan, Borrowers Rating and Loan Original Amount. Particularly we concluded that `interest rate on loans with a larger amount is likely to be lower` and `borrowers with high ratings receive loans at lower interest rates and also have a lower risk of default`. 

## Key Insights for Presentation

> For the presentation, I focused on just the influence of the Employment Status, Dept to Income ratio, Prosper Rating, Recommedations and Loan amount infulance on the main variable. I start by introducing the distibution of Loan Status variable, followed by the other features by using bar plots for the categorical ones and histograms - for the numeric ones. I've made sure to use different color palettes for each quality variable to make sure it is clear that they're different between plots. Afterwards, I investigated the effect of these variables on the main variable using both boxplots and point plots.
