## Problem Overview
This project aims to predict the remaining useful life (RUL) of aircraft engines using LSTM networks, based on sensor data. The objective is to forecast the time to failure of these engines, facilitating proactive maintenance planning. Two main approaches are employed: regression modeling to predict the number of remaining cycles before failure, and binary classification to determine if an engine will fail within a specific time frame.

## Data Description
The dataset contains multivariate time series data for multiple aircraft engines, with sensor readings and the cycle as the time unit. Each engine's data is assumed to be generated independently. The training data includes labeled failure events, while the testing data lacks failure labels. Ground truth data provides the RUL for engines in the testing set.

## Experimental Results
### Regression Model Results
- Mean Absolute Error: 12
- Coefficient of Determination (R^2): 0.7965

Visualizations depict the trend of loss function, MAE, R^2, and actual versus predicted data.

### Binary Classification Results
- Accuracy: 0.97
- Precision: 0.92
- Recall: 1.0
- F-Score: 0.96

Similar visualizations show the trend of loss function, accuracy, and actual versus predicted data.

## Extensions
An extension involves creating a multi-classification model to predict failure within different time windows, expanding the predictive capabilities.

## Citations
This work has been cited in various academic and professional contexts:
- Chapter 10 of "Hands-On Artificial Intelligence for IoT" book
- Chapter 7 of "Mobile and Wireless Communications with Practical Use-Case Scenarios" book
- Master's thesis titled "Using Recurrent Neural Networks to predict the time for an event"
- Paper titled "Exploring Cloud Assisted Tiny Machine Learning Application Patterns for PHM Scenario"

## References
- Relevant notebooks and experiments on predictive maintenance
- Turbofan Engine Degradation Simulation Dataset from NASA Ames Prognostics Data Repository
- "Understanding LSTM Networks" blog post by Christopher Olah

These references provide additional insights and resources for understanding and implementing LSTM-based predictive maintenance models.
