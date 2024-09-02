# Predictive-Modeling-of-Blood-Sugar-Dynamics


**Overview**
This project focuses on improving diabetes management by developing a machine learning system that predicts blood sugar levels using two forecasting models: ARIMA and PROPHET. The system leverages Continuous Glucose Monitoring (CGM) data, carbohydrate intake (CHO), and insulin data to enhance the accuracy of blood sugar predictions and classifications.

**Objectives**
The key goals of this project include:

1- Blood Sugar Prediction: Forecast blood sugar levels using ARIMA and PROPHET models.
2- Model Comparison: Evaluate and compare the effectiveness of ARIMA and PROPHET in predicting blood sugar dynamics.
3- Classification: Categorize blood sugar levels into Hypoglycemic, Normal, or Hyperglycemic states.
4- Continuous Modeling Loop: Implement a continuous prediction loop that forecasts 2 hours ahead, incorporating future carbohydrate intake for dynamic adaptation.
5- Cross-Validation: Refine model accuracy through cross-validation, enhancing the precision of predictions.

**Results**
1- ARIMA Model: Achieved a pre-cross-validation accuracy of 28.81%.
2- PROPHET Model: Achieved a pre-cross-validation accuracy of 57.62%, which improved to 64.70% after cross-validation.
3- Blood Sugar Classification: Enhanced prediction capabilities by categorizing blood sugar levels for better diabetes management.

**Project Structure**
Dataset Folder: Contains the CGM, carbohydrate intake, and insulin data used for modeling.
Code File: Includes the implementation of ARIMA and PROPHET models, as well as the continuous modeling loop and cross-validation processes.

**Conclusion**
This project advances the field of diabetes management by providing a comparative analysis of ARIMA and PROPHET models for blood sugar prediction. The system’s ability to dynamically adapt and classify blood sugar levels offers a significant contribution to improving patient well-being and optimizing diabetes care strategies. Explore the code and dataset to see how these models are applied to real-world health data.
