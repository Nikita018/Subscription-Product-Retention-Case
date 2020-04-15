# Analytics_Case_Study

Goal : Understand Factors that affect Product Retention and provide ballpark numbers for business to define Service Level Agreements (SLA)

Analysis (in SQL) :
1. Found out the Total Contract Value customers have committed to spend (per month in each state)
2. For partners who have purchased more than 1 product, finding the value of the second product purchased by them and the Click market Value

Metric Design : 
Studied the following metrics to measure the quality of services provided to the clients
1. Job Slots
2. Total Contract value
3. Click market Value


Inference 
1. While the contract value is observed to grow across years, only 2 out of 3 customers are renewing the subscription
2. The more value driven to a partner per listing, higher is the renewal rate
3. Prdiciton Likelihood to Retain : Click market Value is the key indicator to Product Renewal. COntracts with greater than $1050 increases renewal likelihood
4. The following additional features can help to detect improvement in customer retention in the ad platform algorithm - Average Monthly Click Rate Growth, Upgrades and Downgrades in Job Slots package, Avergae New Customers added per month, Average customer Churn per month, Fluctuations in Job Listing by an employer

Conclusion : Based on the analysis, the future goal should be to target minimum click market value of $1050 per employer. If we are unable to reach the target click market value for a few months consecutively, we can think of giving our loyal customers bonus job slots or discounts on contract value for a month.

Data and Data description : Provided in the excel sheet
Analysis : SQL and R files
Results : Compiled in the PPT 

