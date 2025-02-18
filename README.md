# Flight Satisfaction Prediction

## __Project Overview__

This project focuses on predicting passenger satisfaction for an airline based on a variety of factors, including demographics, flight details, in-flight services, and overall experience. The model uses an XGBoost Classifier to predict whether a passenger is satisfied with their flight or not. The goal is to enhance customer service by understanding the key factors that influence satisfaction.

## __Key Features__

* __Data Preprocessing__: Categorical features were label-encoded to convert them into numerical values.
* __Exploratory Data Analysis (EDA)__: Conducted visual analysis to uncover relationships between features and passenger satisfaction.
* __Machine Learning Model__: Implemented an XGBoost Classifier to predict passenger satisfaction.
* __Performance Evaluation__: The model's performance was evaluated using accuracy, classification report, confusion matrix, and ROC curve.
* __Visualization__: Created confusion matrix heatmaps and ROC curves to assess the model's accuracy and ability to differentiate between satisfied and dissatisfied passengers.
* __Final Submission__: Generated predictions on test data and saved them into a CSV file for submission.

## __Dataset__

The dataset used includes passenger data related to flight experience and satisfaction, containing the following features:

* __Gender__: Passenger's gender (Male, Female)
* __Customer Type__: Type of customer (Loyal, Disloyal)
* __Age__: Age of the passenger
* __Type of Travel__: Type of travel (Personal, Business)
* __Class__: Class of travel (Business, Eco, Eco Plus)
* __Flight Distance__: Distance of the flight
* __Inflight Wifi Service__: Satisfaction level with in-flight Wi-Fi (Scale 0-5)
* __Departure/Arrival Time Convenient__: Satisfaction with departure/arrival timing
* __Ease of Online Booking__: Satisfaction with the online booking process
* __Gate Location__: Satisfaction with gate location
* __Food and Drink__: Satisfaction with food and drink quality
* __Seat Comfort__: Satisfaction with seat comfort
* __Inflight Entertainment__: Satisfaction with in-flight entertainment
* __On-board Service__: Satisfaction with on-board service
* __Leg Room Service__: Satisfaction with leg room space
* __Baggage Handling__: Satisfaction with baggage handling
* __Check-in Service__: Satisfaction with check-in service
* __Inflight Service__: Satisfaction with in-flight service
* __Cleanliness__: Satisfaction with cleanliness of the flight
* __Departure Delay in Minutes__: Departure delay in minutes
* __Arrival Delay in Minutes__: Arrival delay in minutes
* __Satisfaction__: The overall satisfaction of the passenger (Satisfied, Neutral, Dissatisfied)

## __Technologies Used__

* __Python__
* __Pandas & NumPy__ – Data manipulation and preprocessing
* __XGBoost__ – Machine learning model
* __Matplotlib & Seaborn__ – Data visualization and plotting
* __Scikit-learn__ – Data preprocessing, model training, and evaluation

## __Model Performance__

* __Accuracy__: 95.5%
* __Precision, Recall, F1-Score__: Evaluated for each class (Satisfied, Dissatisfied)
* __Confusion Matrix__: Visualized to show the model's true positives, false positives, true negatives, and false negatives.
* __ROC AUC__: Model's ability to distinguish between satisfied and dissatisfied passengers with an AUC score.
