# KNIME-Lab-3
A continuation of the CRISP- DM method from Lab 2 above.

This lab was about Modeling our Machine Learning, Evaluating it, and Deploying the model for test.
The main areas were to learn how to fine tune our Model by adjusting the hyperparameters. This was done using the For Loop node which was used to iterate through the values to find the best parameters. 
We then evaluated the model on the test set to ensure that it is not overfitting or underfitting the model which might cause a problem to our Machine.
We then went ahead to deploy the algorithm and later export it using the PMML writer and workflow writer node. We also implemented the integrated deployment which eradicates errors in the model in case of changes to the data.

## The 2 KNIME files use different methods to fine tune the data. One majors on the Random Forest while the other one focuses on the Gradient Boosted Trees Model.
## The other file is the Captured WorkFlow. 
Adding a CSV or Excel Reader Node at the beginning of the captured workflow and a CSV writer or Excel writer Node at the end makes the model complete. When you upload your housing Data, the model will give you the predicted outcome.
