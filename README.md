# 100 Days of Machine Learning


**_Day 1_**

#### Types of ML Systems

1. Supervised/Unsupervised Learning

_Supervised_ : Training data includes labels. Eg - Classifcation (learn how to classify - emails), Regression (predict a target numeric value - price of a car)

_Unsupervised_ : Training data is unlabeled. Eg - Clustering.

2. Batch and Online Learning

_Batch_ : System is incapable of learning incrementally: it must be trained using all the available data. It takes lot of time.

_Online_ : Train the system incrementally by feeding it data instances sequentially. Great for systems that receive data as a continuous flow.

3. Instance-Based Versus Model-Based Learning

_Instance-Based_ : System learns the examples by heart, then generalizes to new cases by comparing them to the learned examples, using a similarity measure.

_Model-Based_ : Build a model use that model to make predictions.

##### Main Challenges of ML

- Insufficient Quantity of Training Data
- Nonrepresentative Training Data
- Poor-Quality Data
- Irrelevant Features
- Overfitting the Training Data
- Underfitting the Training Data
- Stepping Back

##### Testing and Validating

- Hyperparameter Tuning and Model Selection
- Data Mismatch
