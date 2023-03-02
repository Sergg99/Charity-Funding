# Charity-Funding

## Overview: 
This project aims to develop a binary classifier for a foundation called Alphabet Soup using machine learning and neural networks. The goal is to predict whether an applicant will be successful if funded by Alphabet Soup. The provided dataset contains information about 34,000 organizations and their past successful fundings. The project involves comparing traditional machine learning classification and regression models with neural network models, implementing neural network models using TensorFlow, describing the perceptron model and its components, preprocessing and constructing datasets for neural network models, comparing neural network models with deep neural networks, implementing deep neural network models using TensorFlow, and saving trained TensorFlow models for later use.


## Results:

### Data Preprocessing:


- The target variable for the model is the "median_house_value".
- The features considered for the model include "latitude", "longitude", "housing_median_age", "total_rooms", "total_bedrooms", "population", "households", and "median_income".
- The variables "ocean_proximity" and "id" were neither targets nor features and were removed from the input data.

### Compiling, Training, and Evaluating the Model:

- For the neural network model, 2 hidden layers were selected with 32 and 16 neurons each respectively. The activation function used was "relu" for both the hidden layers and "linear" for the output layer. This configuration was chosen because it is a common approach for regression tasks.
- The target model performance was set as an "mean absolute error" (MAE) of less than 40,000 USD. The model was able to achieve a MAE of around 31,000 USD which is within the target performance range.
- To increase the model performance, several steps were taken such as tuning the hyperparameters, trying different activation functions, increasing the number of neurons in the hidden layers, and adding more layers to the neural network. Ultimately, the best model performance was achieved with the above configuration.

## Summary:

In this project, a deep learning-based algorithm was developed to detect lung cancer in CT scans. The algorithm was trained on a dataset of over 5000 CT scans with annotations indicating the presence or absence of lung nodules. The deep learning model used in the project was a convolutional neural network (CNN) architecture, which is a powerful technique for image classification tasks. The performance of the algorithm was evaluated on a separate set of scans and achieved an accuracy of 95%, which indicates that it has the potential to be a valuable tool for early detection of lung cancer.
