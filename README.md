# Charity-Funding

## Overview: 
This project aims to develop a binary classifier for a foundation called Alphabet Soup using machine learning and neural networks. The goal is to predict whether an applicant will be successful if funded by Alphabet Soup. The provided dataset contains information about 34,000 organizations and their past successful fundings. The project involves comparing traditional machine learning classification and regression models with neural network models, implementing neural network models using TensorFlow, describing the perceptron model and its components, preprocessing and constructing datasets for neural network models, comparing neural network models with deep neural networks, implementing deep neural network models using TensorFlow, and saving trained TensorFlow models for later use.


## Results:

### Data Preprocessing:

The target variable for the model is marked as successful in the DataFrame, indicating that it has been successfully funded by AlphabetSoup. The IS_SUCCESSFUL column is the feature chosen for this dataset. The EIN and NAME columns are removed from the input data to improve code efficiency.

### Compiling, Training, and Evaluating the Model:

In the optimized model, 
- layer 1 started with 120 neurons with a relu activation. 
- layer 2 dropped to 80 neurons and continued with the relu activation.
- layer 3 the sigmoid activation seemed to be the better fit (40 neurons) and layer 4 (20 neurons).
- The target for the model was 75%, but the best the model could produce was 72.7%. 
- Columns were reviewed, and the STATUS and SPECIAL_CONSIDERATIONS columns were dropped as well as increasing the number of neurons and layers. Other activations were tried such as tanh, but the range that model produced went from 40% to 68% accuracy. The linear activation produced the worst accuracy, around 28%. The relu activation at the early layers and sigmoid activation at the latter layers gave the best results. The next step should be to try the random forest classifier as it is less influenced by outliers.

## Summary:

The relu and sigmoid activations yielded a 72.7% accuracy, which is the best the model could produce using various number of neurons and layers. The next step should be to try the random forest classifier as it is less influenced by outliers.
