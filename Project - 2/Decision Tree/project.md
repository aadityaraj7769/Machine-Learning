# *Build a model in machine learning that predicts whether the person is defaulter or not.*

## Target Variable -> default

1) Import important libraries -> 
    <br>
    numpy      -> for fundamental scientific computations like to create arrays or matrices.
    <br>
    pandas     -> for data wrangling and data manipulation purposes.
    <br>
    sklearn    -> for modeling like using logisticRegression and train test split
    <br>
    matplotlib -> for data visualization and graphical plotting
    <br>
    seaborn    -> it is for visualization library which has some plots like count plot, scatter plot, etc.

2) Read the file (or data) and Look over the data using "head" that will show the top 10(is given) data.

3) Checking its size.

4) Using "describe" we can get the information of all numerical features like its total count, mean, median, std. deviation, min, max, 25%ile, 75%ile, etc.

5) Looking about the information of data using ".info()" and here information means its datatypes and we can also see if there is any missing values in any features.

6) There are many columns whose datatypes are "object" so first change its datatype.

7) Counts of all categorical data, item wise printed.

8) We can do one hot encoding on "purpose, housing, other_credit and job" columns.

9) First we create dummies for those columns which I am doing one hot encoding.

10) I am replacing some categorical data into numerical data or better to say ordinal data.

11) I am splitting my data into train test split where train set contains 70% of the data and rest 30% for the test set.
Random state means splitting data is constant.

12) Now, I am going to build a model using the DecisionTreeClassifier function. Using criteria 'gini' to split.
Gini Impurity -> It measures the frequency at which any element of the dataset will be mislabelled when it is randomly labeled.

Entropy -> Ita measure of information that indicates the disorder of the features with the target.

13) Checking our performance. It is easily observable that my model is overfitting so for reducing overfitting, I am doing some technique.

14) for reducing overfitting, I am limiting the depth = 3.
Now my model is neither overfitting nor underfitting.

15) I am plotting confusion matrix for this model.

16) I am using now ensemble learning technique.
Ensemble learning is a machine learning technique in which multiple individual models, often called base models, are combined to produce an effective optimal prediction model.

17) First is Bagging.
Bagging -> The method of randomly creating samples of data out of a population with replacement to estimate a population parameter.

18) I am getting maximum accuracy when no. of estimators are 66.

19) Second is AdaBoosting.
AdaBoosting -> It is a type of boosting technique that combines multiple “weak classifiers” into a single “strong classifier”.

20) I am getting maximum accuracy when no. of estimators are 15.

21) Third is GradientBoosting.
GradientBoosting -> The cost function or residual ((y - yhat)^2) is being calculated and by using the residual as the output variable, the model is build.

22) I am getting maximum accuracy when no. of estimators are 76.

23) Fourth is RandomForest Classifier.
Random Forest Classifier -> The random forest algorithm is made up of a collection of decision trees, and each tree in the ensemble is comprised of a data sample drawn from a training set with replacement.

24) I am getting maximum accuracy when no. of estimators are 50.

