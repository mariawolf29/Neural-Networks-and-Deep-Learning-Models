# Neural Networks and Deep Learning Models

CSV contains more than 34,000 organizations that have received various amounts of funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization such as the following:

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

Using my knowledge of machine learning and neural network model building, I will create a binary classifier that is capable of predicting whether or not an applicant will be successful if funded by Alphabet Soup using the features collected in the provided dataset.

## Goals:
- Import, analyze, clean, and preprocess a “real-world” classification dataset.
- Select, design, and train a binary classification model of your choosing.
- Optimize model training and input data to achieve desired model performance.

## Analysis:

I was not able to achieve a predictive accuracy higher than 75%. Accuracy of my model is 56.26%, meaning that this model is able to predict the succes of a venture paid by Alpahet Soup 57% of the time.

My model has three hidden layers with 24, 12 and 6 neurons. The hiddend layers have the relu activation function to identify nonlinear characteristics from the input values. In the output layer I use the sigmoid activation function. The model uses the binary_crossentropy loss function, adam optimizer and accuracy metrics.

To increase model performance I increased the number of epochs to allow for the deep learning model more opportunities to optimize the weight coefficients. Other steps to achieve the target model performance were combinig rare categorical values via bucketing, encoding categorical variables using one-hot encoding, standardizing numerical variables using Scikit-Learn’s StandardScaler class.



