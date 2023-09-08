# Predicting Political Parties-1984 Congressional Voting Records

By: Srinath Dittakavi

Overview:
This GitHub repository contains a machine learning project that aims to predict the political party affiliation (Republican or Democrat) of members of the United States Congress based on their voting records on key legislative issues with an accuracy rate of over 95%. The project utilizes data from the 1984 United States Congressional Voting Records dataset, available from the UCI Machine Learning Repository.

So, why did I embark on this adventure? Well, it's all about applying the machine learning and model training skills I've been picking up in my college classes. I wanted to put my classroom knowledge to the test and show that I can use machine learning in a real-world (sort of) scenario. I want to use this as a stepping stone to explore and build bigger and better machine learning and AI tools, leveraging the latest advancements in technology and data science to create innovative solutions that address complex real-world problems.

Dataset Source:
Congressional Voting Records. (1987). UCI Machine Learning Repository. https://doi.org/10.24432/C5C01P.

Key Features:

Data Preprocessing: The project includes data cleaning and preprocessing steps to handle missing values and convert categorical values to numerical format.
Feature Selection: It focuses on 16 key votes identified by the Congressional Quarterly Almanac (CQA) to determine party affiliation.
Machine Learning Model: A neural network-based classification model is implemented using TensorFlow and Keras, designed to predict whether a member of Congress belongs to the Republican or Democrat party based on their voting patterns.
Model Architecture: The neural network architecture consists of multiple layers with dropout and batch normalization to improve generalization and prevent overfitting.
Model Evaluation: Cross-validation is used to assess the model's accuracy in predicting party affiliation, providing a mean accuracy score across different folds.

Dependencies:

tensorflow, scikeras.wrappers, tensorflow.keras, pandas, scikit-learn

Disclaimer:
This project is for educational purposes only and does not aim to make real-world political predictions or influence any political interests.
