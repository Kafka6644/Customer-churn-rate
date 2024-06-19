Dataset taken from IBM base sample (https://www.ibm.com/docs/en/cognos-analytics/11.1.0?topic=samples-base).
Dataset is of a telecom company wanting to know future customer churn rate, based on previous details.

Libraries used is XGBoost.

What I achieved differently is, I built this model not to classify those who stayed at the same company service, but who left (since customers leaving costs the company). Ofcourse this came at a bit price of calculating accuracy for those who did not leave the service. 
