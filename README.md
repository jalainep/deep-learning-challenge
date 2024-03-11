# Deep-Learning-Challenge



![image](https://github.com/jalainep/deep-learning-challenge/assets/143963189/5e4cedc5-6ec5-43f9-998c-441574898f0e)



# Overview

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively



# Results 

Data Preprocessing

What variable(s) are the target(s) for your model? The target variable was IS_SUCCESSFUL column to find successful candidates to be funded.

What variable(s) are the features for your model? The features for the model are EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

What variable(s) should be removed from the input data because they are neither targets nor features? The EIN and NAME variables were removed because they were not targets or features.




Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? I used 3 layers, & 3 activation functions.

Were you able to achieve the target model performance? I was not able to achieve the 75% target performance.

What steps did you take in your attempts to increase model performance?  I dropped the EIN column, & reduced the number of epochs to 75.


# Summary

The results I achieved from the deep learning model was 73%, which was 2 percent less than the 75% target. A possible solution would be to clean up the data, dropping more columns, adding more layers, and/or creating more bins.
