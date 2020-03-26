# Machine Learning - Classification

This repository is a Machine Learning collection of jupyter notebooks containing classification experiments.

## Notebooks

**Dog or Pig?**

This jupyter notebook contains simple train data representing dogs and pigs with three distinct features.
Test data is used to test the model's accuracy score.

**Will they buy?**

This is the first of the notebooks to use external data, as a csv containing the train and test data is loaded from the ```data``` directory.
This test case implements a model that tries to predict whether a website user will buy something from its store.
Predictions are based around the pages the user visited while browsing the website. Such pages are the features.
Test data is used to test the model's accuracy score.

**Will the projected be completed?**

This test case implements a model that tries to predict whether a project will be completed by a freelancer.
Train and test data are loaded from ```data/projects.csv```.
Predictions are based on the amount of hours expected for the freelancer to complete the job and the amount of money the buyer is paying them.
Test data is used to test the model's accuracy score and the accuracy score for the baseline algorithm.
Data visualization libraries, such as seaborn and matplotlib, are also used here.