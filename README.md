# Prosper loan data
## by Teslim Kehinde


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
The dataset can be found [here]( https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.),
with feature documentation available [here]( https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

## Summary of Findings

Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
In the exploration of the principal dataset, I looked out to determining the factors that afffects the Loan status of the data. I found that there was a strong relationship between the Status of the loan and the Term of the loan. I noticed that the nature of the terms of loans that are completed are Intermediate, i.e 36 months. Also noticed that there are more loans on the Intermediate level across all status than any other term. Insinuating that the Term of the loan affects the loan status in a linear way.

From the exploraion, it was quite evident that abandoned loans are 60 months in nature.

In the process of exploration, i noticed that income range of people with 50,000 - 74,999, have there payment to be up to date, while those with income range around 25,000 - 49,999 are completed. 

Thus, it is okay to deduce that the term of the loans and the Income Range of the borrowers affects the Loan Status.

## Key Insights for Presentation

Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

For the presentation, I focused on just the influence of the Terms and Income Range of the borrowers
and left out most of the intermediate derivations. I start by introducing the
Loan Status variable, followed by the pattern in Term and Income Range distribution, then plot the
Cluster bar chart.


