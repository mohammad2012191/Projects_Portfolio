* # Faulty Air Quality Sensor Prediction:
AirQo’s air quality sensing network has more than 120 low-cost devices deployed across Uganda; in most cases, these devices 
are deployed in unmonitored or perilous environments. 
These low-cost electronic devices are susceptible to breakdown caused by communication malfunction, aging, wear and tear, manufacturing 
deficiencies, incorrect calibration, mishandling and other external environmental factors. Faults lead to data 
inaccuracies and data loss, which impacts decisions and policies that could significantly impact people’s lives.
<br />In this challenge, your task is to develop a classification model to identify a device has an off set fault or not, regardless of the device. 
<br />The model can be used by AirQo to automatically flag a device that is returning faulty data.
* # Table of Contents:
  1- Importing Libraries
<br />  2- EDA with some Visualizations
<br />  3- Date Preprocessing:
<br />   - Adding Date-related Features
<br />   - Imputing Missing Values using Moving Window Technique
<br />   - Feature Engineering
<br />   - Encoding (Target Encoder)
<br />   - Oversampling using SMOTE
<br /> 4- Creating a Test Set using the TimeSeriesSplit Function
<br /> 5- Define a LightGBM Model
<br /> 6- Evaluating Against the Test Set using Roll-forward Window Cross-validation
<br /> 7- Making the Final Prediction File

* ## Accuracy: 83.4%
* ## Position: 46 out of 719 contestants
* ## Contest URL: https://zindi.africa/competitions/umojahack-africa-2022-beginner-challenge
