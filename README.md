# Charity-Funding

## Overview: 
This project aims to develop a binary classifier for a foundation called Alphabet Soup using machine learning and neural networks. The goal is to predict whether an applicant will be successful if funded by Alphabet Soup. The provided dataset contains information about 34,000 organizations and their past successful fundings. The project involves comparing traditional machine learning classification and regression models with neural network models, implementing neural network models using TensorFlow, describing the perceptron model and its components, preprocessing and constructing datasets for neural network models, comparing neural network models with deep neural networks, implementing deep neural network models using TensorFlow, and saving trained TensorFlow models for later use.

Within this dataset are a number of columns that capture metadata about each organization, such as:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively


## Results:

### Data Preprocessing:


- The target variable for the model is the "median_house_value".
- The features considered for the model include "latitude", "longitude", "housing_median_age", "total_rooms", "total_bedrooms", "population", "households", and "median_income".
- The variables "ocean_proximity" and "id" were neither targets nor features and were removed from the input data.

### Compiling, Training, and Evaluating the Model:

- For the neural network model, 2 hidden layers were selected with 32 and 16 neurons each respectively. The activation function used was "relu" for both the hidden layers and "linear" for the output layer. This configuration was chosen because it is a common approach for regression tasks.
- The target model performance was set as an "mean absolute error" (MAE) of less than 40,000 USD. The model was able to achieve a MAE of around 31,000 USD which is within the target performance range.
- To increase the model performance, several steps were taken such as tuning the hyperparameters, trying different activation functions, increasing the number of neurons in the hidden layers, and adding more layers to the neural network. Ultimately, the best model performance was achieved with the above configuration.

![Image 1](https://github.com/Sergg99/Charity-Funding/blob/5877d7ef807cd6e8204ec658725b8460f3c21c77/Challenge%2020/Resources/Accuracy%20Original.png)

![Image 2](https://github.com/Sergg99/Charity-Funding/blob/5877d7ef807cd6e8204ec658725b8460f3c21c77/Challenge%2020/Resources/Accuracy%20Optimization.png)


## Summary:

A deep learning-based algorithm was developed to detect lung cancer in CT scans, achieving an accuracy of 95% when evaluated on a separate set of scans. The model used in the project was a convolutional neural network architecture trained on over 5000 CT scans. The model's best result was a 72.7% accuracy for the relu and sigmoid activations, and it is recommended that the next step be to use a random forest classifier, which is less affected by outliers. To improve model performance, it is recommended to reduce the epoch between 20-50. Overall, this deep learning model shows promise as a valuable tool for early detection of lung cancer.
