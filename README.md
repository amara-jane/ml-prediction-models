# Machine Learning Final Project
### A comparison of predictive machine learning models for Asian American societal satisfaction.

For my final undergraduate year machine learning module, I compared predictive machine learning models on 2,653 observations from Pew Research Center survey data on Asian American satisfaction in the US using R. The methods tested include logistic regression, tree-based models, gradient descent and penalised logistic regression. Below is a short summary of the motivation behind the project, the methods used and the conlclusion.

## Motivation 
Developing models to predict Asian American satisfaction with national direction can provide insights into their voting behavior, which is particularly valuable in swing states where their votes can influence the outcome of elections. Predicting public satisfaction is essential for fostering an inclusive and responsive society. Integrating machine learning tools with culturally competent research practices can ensure that the shaping of future policy is representatively informed and attuned to key voters.

## Methods
The following steps were taken to reach the final conclusion.
- Data preprocessing: Dealing with missing values, metadata, categorising, recoding.
- Model training: Logistic regression, tree-based models, gradient descent and penalised logistic regression.
- Model tuning: Feature selection/dimensionality reduction, tuning parameters.
- Model evaluation: Missclassification/error rates, confusion matrices.
- Performance comparison.

## Conclusion
Random forest was the most accurate model, with a missclassification rate of  0.16%. This was a good improvement on the baseline logistic regression model, with a missclassification rate of  0.24%.

## Data and Files

This repository contains the R markdown file containing all code and a pdf knit from the Rmd. 

Here is the link to the publicly available Pew Research Center data from the 2022-23 Survey of Asian Americans: https://www.pewresearch.org/dataset/2022-23-survey-of-asian-americans/

The project was completed on 03/06/2025.
