This is my individual repository for the Home Credit Project for IS 6812, Capstone 1. 

**Business Problem:**

The business problem is to identify likely loans that will default given multiple datasets from the
Home Credit Kaggle Project. There is a 92/8% distribution of the target variable, which shoed some
difficulties throughout development.

**Files:**

The EDA is my initial notebook written in R.

The my_models.ipynb file is written in Python. There isn't as much text in this notebook, but it shows
the steps for cleaning and processing the data and performance for each model. There were some models created 
that I did not get to totally get to finish, like an ANN model.

**Our Solution:**

We found that adding more "real life" types of features boosted our AUC score for the model. Things like 
credit to income ratio, percentage of life employed, trends in paying back the loans, etc. The things that 
a company may like to know about a person essentially that describes their habits and patterns. This is,
obviously what the data shows us, but develping some new features that explored potential key habits in
the individuals behavior was what made a large impact on the models.

**Business Value:**

By getting a higher AUC score, it gives a stronger realm of possibilities to discover the ideal threshold
for the probabiity that someone may default. Depending on what the company values or how they classify
their cost and benefits for each part of a confusion matrix, boosting the AUC gives them the best possible
chance to find the ideal value.

A goal would be to develop a strategy in order to provide rates for each of the possible confusion classifications.
This could derive a formula of a cost benefit analysis to decide the best possible threshold.

**My Contribution:**

All this work in this notebook is my own. I developed this after the group modeling assignment. We ultimatley
moved forward with my LightGBM model.

**Group Struggles:**

Understanding exactly what AUC was and getting everyone on board was a struggle. Understanding best practices
for modeling notebooks like this, especially in python, was also tough. Getting GitHub to work with the whole
group might have been the hardest thing to get right.

**My Learning**

I found the modeling to be the most fun part of the project. The satisfaction from improcing models and understanding
the data deeper in order to derive better feature engineering was slightly addicting.

I also learned how to apply the ultimate AUC metric to a business case and the trade off between higher and lower
accuracies depending on what the business values. 

Learning to work to each of our group members strengths was also a learning experience. I think we all found an avenue
to contribute to our fullest potential.
