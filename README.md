# Prosper Loan Data Exploration
## by Ludmila Mucavele


## Dataset

The data explores the Prosper Loan dataset that contains 113,937 loans with 81 variables on each loan, 
including loan amount, borrower rate (or interest rate), current loan status, borrower income, 
and many others. The last update of the dataset was in 03/11/2014.
The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv);
The variables dictionary can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

In the exploration, plotting the count distribution of the loan status, I found most of the loans were 
currently being paid in that season, but many of them were completed too. 

Looking for the employment status distribution, I saw that most of the borrowers are employed, followed 
by full-time and self-employed borrowers. 

Most of the loans belong to the listing category of Loan for Debt Consolidation followed by the listing 
category for Not Available and 7 Loan for Other reason, what could mean that a great amount of loans for
Debt Consolidation can belong to employed borrowers.

It was found the relationship between loan original amount and monthly loan payment, and taken a closer look 
through the scatterplot distribution. The Loan Original Amount is highly related to Monthly Loan Payment 
positively, meaning that the higher the Loan Original Amount, the higher the Monthly Loan Payment gets.

Throgh box plots, I could see that borrowers with the highest loan original amount are the Employed ones, 
where they can borrow 5000 ($) or more. It can happen to have borrowers with Stated Monthly Income of 0 ($), 
even if they are employed. 
The Part-time, Not Employed and Retired Borrowers are not likely to make loans that require a high monthly payment.

Most of the borrowers to do not fail in paying the loan on time too, especially the borrowers with a high 
loan original amount, that do not tend to make the payment later.


## Key Insights for Presentation

For the presentation, I focus on loan original amount count and status, so as the influence of the 
borrowers in relation to its characteristics. I start by introducing the
loan original amount variable, followed by the loan status count distribution.

After that, I introduce the relation between the loan original amount and the monthly loan payments, that will 
be mentioned further.

Afterwards, I introduce the categorical variable employment status that can be useful to show 
the relationship between the borrowers and the loan features, since in the exploration, the monthly loan payment, 
the number of late payments per month and the loan original amount were impacted by them.
