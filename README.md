# Prosper-Loan-Data-Investigation

> **In this investigation, I will be examining features of loans dataset that could predict a borrower's APR (main feature of interest for the investigation) (univariate exploration). Additionally, I will also explore how certain variables will interact with each other and how they also might affect the relationship of a Borrower's APR with other features (bivariate and multivariate exploration).

>  In my analysis, the relationships that were explored are "BorrowerAPR" vs "Original Loan Amount" and then investigated whether term/employment status has an effect on that relationship. The variables that were investigated in the dataset were the following:

> <b>Term-</b> The length of the loan expressed in months.

> <b>EmploymentStatus-</b> The employment status of the borrower at the time they posted the listing.

> <b>IsBorrowerHomeowner-</b> A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.

> <b>CurrentCreditLines-</b> Number of current credit lines at the time the credit profile was pulled.

> <b>DebtToIncomeRatio -</b> The debt to income ratio of the borrower at the time the credit profile was pulled. This value is Null if the debt to income ratio is not available. This value is capped at 10.01 (any debt to income ratio larger than 1000% will be returned as 1001

> <b>StatedMonthlyIncome-</b> The monthly income the borrower stated at the time the listing was created.

> <b>IncomeVerifiable-</b>The borrower indicated they have the required documentation to support their income.

> <b>LoanOriginalAmount-</b>The originiation amount of the loan
