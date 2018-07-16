# predict-first-drive
A ridesharing company is interested in predicting which driver signups are most likely to start driving. A sample dataset of a cohort of driver signups is provided and includes several pieces of background information gather about the driver and their car. Here we want to use this data set to  understand what factors are best at predicting whether a signup will start to drive, and offer suggestions to operationalize those insights.

# summary of findings
- About 11% of sign up ended complete first trip. 
- The median days spent from signup to complete first trip is 11 days.
- there is a a funnel from signup, background check, adding vehicle to finally complete the first trip. 
- there is a bottleneck in the funnel in adding vehicle. 
- a random forest model is built for prediction and achieve a AUC of 0.91. 
- The predictive model can be used to efficiently allocate resources to help those who might not complete the first trip based on their background information. 
