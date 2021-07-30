# descision_trees_W8
# Regression_DSC_W7
#### {Regression Analysis}, {30/07/2021}
#### By MILDRED KULEI
## Description
Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid.

Part 1: Decision trees:

For this section, you should build a model that makes the above prediction. You should not use individual decision trees, rather you should use at least 2 out of the 3 advanced models we have studied: Random forests, Ada boosted trees, and gradient boosted trees.
Try and optimize each of the 2 models, making sure to document how you've set up your hyperparameters.
Identify which of the 2 models you trust most, and use your model to determine which features are most impactful in influencing the prediction
Note that with decision trees, you don't need to do a lot of data cleaning. This will be very different with SVM.
Part 2: SVM:

In this section, you may be required to clean the data a little bit so as to make sense of the features.

Document what transformation you've done on the data.

Apply Polynomial, linear and rbf kernel function to build your SVM model and then evaluate their performance and pick the kernel that performs the best. Remember to tune your parameters to improve the performance of your model. To make your life easier, make sure to visualize the models you've created. Use any two features to build the models for this step.

Hint: You may want to use decision trees to give you the most preferable features you can use. but also keep in mind that those features might not be suitable for SVM. It might be a good idea to graph them first.

After getting your best performing kernel, use this kernel together with your tuned parameters and repeat the prediction but this time using additional features. Compare the model you've just created with the 2-features version.
## Motivation
This project was done as part of an assessment for Data science core Machine learning course.
## Summary for analysis
1.Defining the question
2.Importing the libraries
3.Reading the data
4.External data source validation
5.Data cleaning
6.Exploratory data analysis(Univeriate summaries)
7.Modelling
8.Implementing solution
9.Challenging solution
10. Follow up question
## Setup/Installation Requirements
* Use google colab for data reparation and analysis.
* Import pandas, matplotlib, SEABORN, sklearn, and numpy lybraries.
## Known Bugs
There were no known bugs.
## Technologies Used
* Python
### License
Copyright (c) {2021} **{MILDRED KULEI}**
