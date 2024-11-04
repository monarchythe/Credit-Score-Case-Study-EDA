# Project: Loan Default Analysis using EDA
## Business Understanding
When a loan application is submitted, the company must make a decision based on the applicant's profile. Two primary risks are associated with the company's decision:

If an applicant is likely to repay the loan, not approving it results in lost business.
If an applicant is likely to default, approving the loan leads to financial loss.


## Dataset Description
The dataset provides information on loan applications and presents two main scenarios:

1. Clients with payment difficulties: Individuals with late payments exceeding X days on at least one of the first Y installments.
2. Clients with on-time payments: Individuals who consistently made timely payments.


When a client applies for a loan, the company can take one of four actions:

1. Approved: The loan application is approved.
2. Cancelled: The client cancels the application during the approval process.
3. Refused: The company rejects the loan due to unmet requirements.
4. Unused offer: The client cancels the loan at a later stage.
## Objective
Through EDA, I have explored how consumer and loan attributes correlate with the likelihood of default. This analysis aims to support the company in making better-informed lending decisions, helping to reduce financial risk and missed business opportunities.
## Data understanding 
This dataset has 3 files as explained below: 
1. 'application_data.csv'  contains all the information of the client at the time of application.
The data is about whether a client has payment difficulties.
2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.

