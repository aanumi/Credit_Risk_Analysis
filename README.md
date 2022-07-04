# CREDIT_RISK_ANALYSIS

## OVERVIEW
In this analysis, we are analyzing data from a credit card data set to determine applicant  viability. We will test the data to identify high & low-risk applicants. The analysis will use different sampling methods (oversampling & under sampling methods) to determine accuracy and classify applicants into high & low risk applicants. Other methods combined the over & under sampling methods, while the last 2 models were used to reduce the occurrence of bias.

## RESULTS
###Listed below are results from all six models used in analyzing this dataset.

	◦	Naive Random Sampling: This model resulted in accuracy of 64.797%. The precision and recall scores for high & low-risk resulted in 0.01 & 0.61; and 1.00 & 0.69. Results are displayed below for support.
<img width="516" alt="Screen Shot 2022-07-03 at 10 50 53 PM" src="https://user-images.githubusercontent.com/100884241/177075466-32922776-61b0-4b1d-94f0-ad5936bed19b.png">

	◦	SMOTE Oversampling: This model resulted in accuracy of 63.6%. The precision and recall scores for high & low-risk resulted in 0.01 & 0.62; and 1.00 & 0.65. Results are displayed below for support.
<img width="518" alt="Screen Shot 2022-07-03 at 10 51 50 PM" src="https://user-images.githubusercontent.com/100884241/177075505-2e4237f0-bdc2-41dd-90bb-6a68cb35f434.png">

	◦	Undersampling: This model resulted in accuracy of 63.6%. The precision and recall scores for high & low-risk resulted in 0.01 & 0.62; and 1.00 & 0.65. Results are displayed below for support.
<img width="511" alt="Undersampling" src="https://user-images.githubusercontent.com/100884241/177075627-dead716d-5c93-4ecc-adff-fb0d3d45ce19.png">

	◦	Combination (Over & Under Sampling): This model resulted in accuracy of 63.76%. The precision and recall scores for high & low-risk resulted in 0.01 & 0.70; and 1.00 & 0.57. Results are displayed below for support.
<img width="528" alt="Screen Shot 2022-07-03 at 10 53 05 PM" src="https://user-images.githubusercontent.com/100884241/177075654-e453ad1e-8f28-43e8-86b9-0861529f496f.png">

	◦	Balanced random forest: This model resulted in accuracy of 80.5%. The precision and recall scores for high & low-risk resulted in 0.03 & 0.71; and 1.00 & 0.90.  Results are displayed below for support.
<img width="520" alt="Balanced random forest classifier" src="https://user-images.githubusercontent.com/100884241/177075694-8f345446-2675-4f1a-851b-a0917e47d714.png">

	◦	Easy ensemble: This model resulted in accuracy of 92.6%%. The precision and recall scores for high & low-risk resulted in 0.08 & 0.91; and 1.00 & 0.94. Results are displayed below for support.
<img width="515" alt="Easy ensemble" src="https://user-images.githubusercontent.com/100884241/177075724-3f7ce03b-d17e-4311-8d4c-15a7f91e11f8.png">


## SUMMARY
From the analysis and results displayed, the balanced random forest & easy ensemble seem to have a higher level of accuracy at 80.5% and 92.6%. The other models show accuracy results ranging from 63 - 64%. The Easy Ensemble model seems to trump the balanced random forest model with an accuracy of 92.6%, with high-risk score of 0.08/ 0.91. For this reason, I would recommend the Easy Ensemble Model.
