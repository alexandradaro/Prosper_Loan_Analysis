# Prosper Loan Data Exploration
## by Alexa Ighodaro

## Dataset
The dataset being used for this project is the Prosper loan Dataset, provided by Udacity. There are 113,937 loans in the dataset with 81 features. 
Most variables are numeric and categorical in nature. </br>
The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000) </br>
The dataset features two main categories:
* Borrower information
* Loan performance information

## Summary of Findings
For this exploratory analysis, my main interest was to analyze the borrowers' information for relationship insights with the loans they took. </br>
Looking at the individual variables, one of the insightful information discovered was that CA State has the highest borrowers.
Looking at borrowers' employment status, I discovered majority of the borrowers have either employed or fulltime employment status. 
Investigating further into their source of income, I discovered that their income mostly ranges from ($)25,000-74,999 and their monthly income distribution is skewed to the right and they are usually less than ($)30k. Their income ratio is right skewed as well. 
Looking at the loan terms, they were either for a period of 12, 36 or 60 months. Most of the loans have a loan term of 36 months.
I extracted the months and years of the loans from the loan original date and I discovered alot of loans were taken in 2013 and I think this is an important insight to present.

Investigating further to observe the relationships between 2 variables, I discovered that the borrower interest Rate is negatively correlated with the loan original amount, which mean the more the loan amount, the lower the Borrower Rate. It also shows that at different size of the loan amount, the Rate has a large range, but the range of interest Rate decrease with the increase of loan amount. I will be showing this in the explanatory presentation.
Looking at the monthly income of borrowers, I discovered that the loan original amount is positively correlated with the stated monthly income. That is, the higher their stated monthly income, the higher the loan amount borrowed. 
Also, borrowers with verified income tend to have a higher average loan amount than borrowers without verified income. 
Borrowers with income ranging from ($)50,000-100,000+ are majorly homeowners.
Borrowers who are employed and fulltime on average take out larger loans than other groups.
There is a strong positive relationship between term and loan amount (longer the term, the larger the loan). Also, Employed borrowers tend to take loans of term duration as 36 months while borrowers with full time employment status tend to take loans with term duration of 12 months.
Looking at loan origination over years, I observed that in 2008-2009 there was a large dip in loan origination that went back up in 2013.

Investigating further using multiple variables, I realized that loan Term didn't really seem to have effect on the relationship between borrower rate and loan original amount.
Also checked if verified income has an effect on the loan original amount and relationship with income range. Then I discovered that people who earn ($)100,000+ and have verified their income tend to get larger loan original amount than those whose income are not verifiable. 


## Key Insights for Presentation
For the presentation, I focus on the journey of exploring the features of interest to discover the relationship between the borrowers and the loans they took.
I introduced the features of interest, followed by how they relate to one another and eventually how their correlation is affected by another variable.
Features include: Borrowers' employment status, their income range, stated monthly income and the loan original amount. 
