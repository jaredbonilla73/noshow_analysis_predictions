# noshow_analysis_predictions
No-Show Status Analysis and Predictions(python) 
 ## Problem/Goal
 -When a client misses an appointment with the status "No-Show", the agency loses money for allocated time slot. The goal in this study is to try and find underlying patterns in clients based on demographic, geographical and appointment history to assess if certain variables play an effect on the likelihood of a client provide the agency a foundation to minimize this issue and save money. 
 
 ## Clean Data:
 - Rename columns and string values in columns.
 - Change date and time to date time values.
 - drop columns not needed for analysis.
 
 ## Feature engineer:
 - Create features to make bins for other features(ex.time frame, age range)
 - Create features for client and therapist attendance percentages.
 
 ## Exploratory Data Analysis:
 - Visually summarize data.
 - Identify trends and patterns among No-Show and Seen/Billed appointments.
 - Cluster and analyze No-Show clients to look for similiarities.
 
 ## Prepare and Predict:
 - Change all status' to seen or not seen.
 - One hot encode categorical columns.
 - Predict using Logicistic Regression,Random Forest, Gradient Boost.
 
 ## Results:
 - Gather features of importance.
 - Describe insight in terms applicable by an agency that doesnt use data science or analytics. 

