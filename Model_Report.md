# Neural Network Model Report

## Overview
The purpose of this Alphabet Soup Analysis was to create a binary classifier to predict whether applicants will be successful if funded by Alphabet Soup.  With a CSV file of data from over 34,000 organizations, we will have ample information to analyze.

## Results

- Data Preprocessing
    - The target variable for our model is the 'IS_SUCCESSFUL' column while the feature variables of our model are the rest of the columns from our DataFrame.

- Compiling, Training, Evaluating
    - I selected 80 units for my first hidden layer (with an input dimension of 42), 30 units for my second hidden layer and one unit for my output layer (for a total of 3 layers).
    - I changed a bit of binning as well as a small change to my input dimension number to hopefully increase target performance.  Unfortunately, I was not able to reach the targeted performance number