# US-Census
The US Census dataset contains personal (but anonymized) information about 300 000 american inhabitants.
The goals of this project is to predict, given an inhabitant's characteristic, whether she/he will earn more or less than $50 000 a year.

# Data Cleaning and data exploration
We start by removing unnecessary variables, and explore the characteristics of people who earn more than $50 000 a year.
We try to avoid keeping variables which are too much correlated.
We do another preprocessing part: 
- Continuous variables are normalized (remove mean and divide by the standard deviation)
- Categorical variables are "dummified"

# Predictions
We try several classification algorithms

# Evaluation
We use first accuracy as a way to check the validity of the predictions. We also use recall and F1-score.
