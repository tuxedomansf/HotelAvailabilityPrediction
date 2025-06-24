# HotelAvailabilityPrediction
Business Logic:
Travel Express is an online hotel booking agency. Each hotel that accepts bookings throughout the year adds value to the company's reputation. However, recently, managers have noticed that customers are unhappy with certain hotels that have become unavailable for booking. The company has decided to fund hotels based on their commitment to yearly availability and is interested in developing a model to predict hotels yearly availability. The target feature is
'yearly_availability' with two values: '1' indicating that the hotel accepts bookings for 365 days in a year, and 'O' indicating it does not. Some of the data fields have bugs or typos that need to be fixed.
The deliverables are well-documented Jupyter notebook, and "submissions.csv" with predicstions.

Data Sets and Schema:
Data sets
"train.json" -- data used to train the model, in JSON format
"test.csv" -- data used for prediction
"submissions.csv" -- populate this file with the results
"sample_output.csv" - sample reference of submission file data

Technical Specifications:
Exploratory Data Analysis and Feature
Engineering
Prepare the data for analysis
Drop any rows that are missing a value for a feature.
Find and fix data bugs in the "region" and
"accommodation_type" fields
Add new features related to the original time-series variable.
Use encoding of categorical features wherever it is necessary.
Identify the features that are most important to the model's performance.

Predictive Modeling and Model Evaluation
Design a modeling pipeline to predict
"yearly_availability" as the target feature. The pipeline should have at least one predictive model. Use of multiple models is optional.
Assess model performance on "train.csv" by using the "Accuracy" metric, i.e., the number of correct predictions divided by the total number of predictions.
Submission:
Predict the "yearly_availability" feature for "test.csv". The result should be a table with two columns, "id" and
"yearly_availability". The "yearly_availability" column should have "0" or "1" values.
Save the results in "submissions.csv". Include a header with column names. An example is provided in "sample_output.csv".
Test Evaluation:
The score will be automatically evaluated based on the value of the Accuracy metric for the
"submissions.csv" file. Get the best possible value of the metric during model development.
The reviewer might dive deeper into the Jupyter notebook and the visualization to get more context.
