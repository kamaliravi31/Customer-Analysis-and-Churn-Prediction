# Customer Analysis and Churn Prediction

## Introduction
This project aims to predict and prevent customer churn. By accurately identifying customers who are likely to churn, the project seeks to provide actionable recommendations to improve customer retention and enhance overall service quality.

## Objectives
1. **Clean Data**: Prepare the dataset by removing inconsistencies.
2. **Exploratory Data Analysis**: Visualize and understand the data.
3. **One-Hot Encoding**: Convert categorical columns to numeric format.
4. **Data Preprocessing**: Scale and format data for model training.
5. **Train and Test Split**: Divide data into training and testing sets.
6. **Build Classification Model**: Develop a model using Artificial Neural Networks (ANN).
7. **Predict Dependent Variable**: Use the model to predict customer churn.
8. **Evaluation Metrics**: Assess model performance with metrics.
9. **Confusion Matrix**: Visualize performance using a heat map.

## Description

### Data Wrangling
- **Task**: Remove null values and ensure all variables have the correct data types.
- **Outcome**: A clean and consistent dataset ready for analysis.

### Exploratory Data Analysis
- **Task**: Create visualizations to understand data distributions and relationships between variables of how tenure and monthly charges affect the churn rate 
- **Outcome**: Comprehensive visual insights that help in understanding customer behavior and identifying key factors affecting churn.

<img src=https://github.com/kamaliravi31/Customer-Analysis-and-Churn-Prediction/blob/main/images/tenure.png>


<img src=https://github.com/kamaliravi31/Customer-Analysis-and-Churn-Prediction/blob/main/images/month_charges.png>

### One-Hot Encoding
- **Task**: Convert categorical variables into numeric format and encode them as binary fields.
- **Outcome**: Transformed categorical data that can be easily used to predict the dependent variable.

### Data Preprocessing
- **Task**: Standardize the values of different features to a common scale using MinMaxScaler from the sklearn library.
- **Outcome**: Preprocessed data that ensures all features contribute equally to the model training process.

### Train and Test Split
- **Task**: Split the dataset into 80% training data and 20% testing data, with independent variables as X and the dependent variable as y.
- **Outcome**: Two datasets that allow for effective training and evaluation of the model.

### Build Classification Model
- **Task**: Develop an artificial neural network using TensorFlow and Keras libraries to classify whether a customer will churn.
- **Outcome**: A trained ANN model capable of predicting customer churn based on input features.

  <img src=https://github.com/kamaliravi31/Customer-Analysis-and-Churn-Prediction/blob/main/images/ANN_model.png>

  <img src=https://github.com/kamaliravi31/Customer-Analysis-and-Churn-Prediction/blob/main/images/model_evaluation.png>

### Predict Dependent Variable
- **Task**: Use the trained model to predict whether a customer will churn.
- **Outcome**: Predicted churn values for the testing dataset.

### Evaluation Metrics
- **Task**: Assess the performance of the classification model using classification reports and accuracy scores.
- **Outcome**: Detailed evaluation metrics that provide insights into the model's accuracy, precision, recall, and F1-score.

<img src=https://github.com/kamaliravi31/Customer-Analysis-and-Churn-Prediction/blob/main/images/classification_report.png>



### Confusion Matrix
- **Task**: Visualize the confusion matrix using a heat map to understand the model's performance in terms of true positives, false positives, true negatives, and false negatives.
- **Outcome**: A heat map that visually represents the model's accuracy, with an achieved accuracy of 78%.

<img src=https://github.com/kamaliravi31/Customer-Analysis-and-Churn-Prediction/blob/main/images/confusion_matrix.png%20.png>

## Conclusion
This project successfully developed a customer churn prediction model using artificial neural networks. The model achieved an accuracy of 78%, providing a solid foundation for further improvements. The insights gained from the exploratory data analysis and the recommendations based on model predictions can help the company take proactive measures to enhance customer retention and service quality.
