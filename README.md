# Data-Visualization
Udacity Data Analysis Final Project
Check the Home Folder

Prosper Loan Data Analysis
by Jessie Ifeanyi
Dataset
The dataset have chosen to analyze the Proper Loan data set. Prosper was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than $18 billion in loans to more than 1,060,000 people. The original dataset we are exploring contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. See this data dictionary to understand the dataset's variables. I have refined and dropped some columns that I will not be using for this exploration before starting.

Here, we try to answer questions like:

What factors affect a loan’s outcome status? What affects the borrower’s APR or interest rate?.

The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. The dataset feature documentation available can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0,

Summary of Findings
Prosper Loans gave move of its loans to employed customers. This is good because they are more likely to have the capacity to payback their loans. So most of the loans are medium term loans (for 36 months) while annual loans are so few, even negligible. Let's see what further investagation on what happened before and after 2009 with regards Prosper credit rating/grade.

The Prosper Rating assigned at the time the listing was created: 0 - N/A, 1 - HR, 2 - E, 3 - D, 4 - C, 5 - B, 6 - A, 7 - AA. Applicable for loans originated after July 2009. The illustrations shows most loans rating lie between A and D (3-6) which is fair enough. Both data are slightly normally distributed.

Another important feature we explore here is the BorrowerAPR. This is the Borrower's Annual Percentage Rate (APR) for the loan. The insights tells us that on the average the APR lie between 10 and 35%, averagely 20%. Loans APR even go as high as 40%. The might increase the likelihood of incurring bad debts. Most people are taking Prosper loans to pay off other loans they already incurred. The likelihood of these turning out to be good debt is low as they are current not capable of paying of previous debt themselves

As expected, there is a negative correlation between Credit Score and Borrower APR since the lower the credit score, the higher the borrower APR in case of delinquencies. However, there is no significant correlation between TotalProsperLoans vs Amount deliquent.

The CreditScoreRangeLower represents data for lower value representing the range of the borrower's credit score as provided by a consumer credit rating agency.

The scatter plot above shows that the borrower's credit score and the borrower APR has no corellation in themselves. as shown the darker purple at the top indicating high credit scores and borrowing for debt consolidation

This shows us that high credit score does not mean borrowing for other reasons other than debt repaymen

Key Insights for Presentation
For the presentation, I just focus on explaining what factors affect a loan’s outcome status, what affects the borrower’s APR, if there are differences between loans depending on employment status. I also investigated the ralationship between different features in the dataset and their ossible impact on the loan outcome/status
