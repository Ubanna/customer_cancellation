## PREDICT CUSTOMER CANCELLATION

### Background:

In an industry dictated by the enrollment of customers in a particular
plan or membership, the ability to retain customers directly impacts the
bottom line of company performance.

Identifying driving attributes of customers likely to churn, provides the
business actionable insight to make modifications or adjustments in their
outreach attempts with higher risk features.
Additionally, identifying which services or features of a particular
customer profile that lead to high retention drive understanding of
product offerings, services and customer profiles that are best suited.

### Business Question:

Based on the last six months of customer activity, will the customer
cancel in the next 30 days?

### Data Set Structure Guidelines:

Source of data - Kraken ML Platform

Customer transaction record detail; with a single customer represented in
each row of the data set.

Subsequent features or attributes of each
customer are represented in the columns proceeding the account ID
(customer) with a target column of cancelled included; this will be the
value we will predict on.

The "History" file is used to train the model, and the "PredictMe" file
is used to create predictions from the trained model. The "PredictMe"
data file is identical to the "History" file, except that all values in
the target column are blank.
