This is my individual repository for the Home Credit Project for IS 6812, Capstone 1. 

**Business Problem**
The business problem is to identify likely loans that will default given multiple datasets.

**Files:**
The EDA is my initial notebook written in R.

The individual_modeling_home_credit file is written in Python. There isn't as much text in this notebook, 
but it shows the steps for cleaning and processing data and scores for each test. There were some models 
created that I did not get to totally get to finish, like an ANN model.

**Our Solution**
Finding more "real life" types of features boosted our AUC score for the model. Things like credit to
income ratio, percentage of life employed, trends in paying back the loans, etc. The things that a company
may like to know about aperson essentially.

**Business Value**
By getting a higher AUC score, it gives a stronger realm of possibilities to discover the ideal threshold
for the probabiity that someone may default. Depending on what the company values or how they classify
their cost and benefits for each part of a confusion matrix, boosting the AUC gives them the best possible
chance to find the ideal value.

**My Contribution**
All this work in this notebook is my own. I developed this after the group modeling assignment. We utlimatley
moved forward with my LightGBM model.

**Group Struggles**
Understanding exactly what AUC was and getting everyone on board was a struggle. Understanding best practices
for modeling notebooks like this, especially in python, was also tough. 
