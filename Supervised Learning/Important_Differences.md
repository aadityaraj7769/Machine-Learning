1) Supervised and Unsupervised Learning

    **>>** **Supervised Learning** &nbsp;&nbsp;&nbsp;&nbsp; -> When we know that there is an output and it has labelled data. When we train the machine using data that is well   labelled.
                                  **Example**:- Suppose we have a basket full of fruits that we know already because parents trained us already when we were young 
                                            and if someone asked some fruits from the basket and we are able to identify the fruits because we already trained.

    **>>** **Unsupervised Learning** -> When the training of machine using information that is not labelled and machine is to group information according to its
                                  similarities.
                                  **Example**:- Suppose we have a basket full of fruits that we never seen before and someone asked to keep it separate so we will   separate according to its similarities.


2) Regression and Classification

    ***Both are the type of Supervised Learning***

    **>> Regression**   &nbsp; &nbsp;&nbsp;&nbsp; -> When the output is numerical we say that this is a regression problem. &nbsp;&nbsp; **Example**:- Price of a car

    **>> Classification** &nbsp;-> When the output is categorical we say that this is a classification problem. **Example**:- Whether a person is diabetic or not


3) Linear and *Logistic* Regression

    **>> Linear Regression** -> It is one of the machine learning algorithm that is used for predicting the continuous dependent variable with the help of independent variable.    **Example**:- y = mx + c

    **>> Logistic Regression** -> It is also one of the machine learning algorithm that is used for predicting the categorical dependent variable with the help of dependent variable and it can only between 0 and 1. **Example**:- log(Y/(1-Y)) = b0 + b1X1 + b2X2 + ... + bnXn

4) Bias and Variance

    **>> Bias** -> When a difference occurs between actual values and predicted values made by model is known as bias.

    *Ways to reduce High Bias -> 1) Increase the input features as the model is underfitted.
                                                2) Decrease the regularization term.*

    *Example:-*  Machine learning algorithms with low bias are Decision Trees, k-Nearest Neighbours and Support Vector Machines and algorithm   with high bias is Linear Regression and Logistic Regression.

    **>> Variance** -> It tells that how much a random variable is different from its expected values. High variance model leads to overfitting.

    *Ways to reduce High Variance -> 1) Increase the training data. 
    2) Increase the Regularization term*


5) Bagging and Boosting

    **Both are the types of Ensemble Learning**

    **>> Bagging** -> It is a weak learner model that learn from each other independently in parallel and combines them for determining the model average.
                        

        **Implementation Steps of Bagging** -> 
                        **Step 1**: *Multiple subsets are created from the original data set with equal tuples, selecting observations with replacement.*
                        **Step 2**: *A base model is created on each of these subsets.*
                        **Step 3**: *Each model is learned in parallel with each training set and independent of each other.*
                        **Step 4**: *The final predictions are determined by combining the predictions from all the models.*
                        
    **>> Boosting** -> It is also a weak learner model but works differently from bagging. Here learners learn sequentially like first it creates a model and it gives more priority to the data which gives wrong output and again creates another model.

6) Gini and Entropy

    

7) AdaBoost and GradientBoost and XGBoost
8) Why XGBoost is comparatively better?
9) Correlation and Covariance
10) K-nearest neighbours (KNN)
11) Why KNN is also known as lazy learning algorithm?
12) Euclidean and Manhattan Distance

