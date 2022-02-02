# mie1628-project
UofT MIE 1628 project: Data Analysis of Bank Market Campaign
- Created machine learning models to predict customer's subscription rate after marketing campaign

Dataset: Bank Marketing Dataset (https://archive.ics.uci.edu/ml/datasets/Bank+Marketing )     

Nowadays, marketing campaigns are widely used in the industry to promote products and services. There are 2 main types of marketing campaigns: mass campaigns and targeted campaigns. Mass campaigns face to the general public, which rarely get subscription response. While, targeted campaigns targets a specific group of people who are willing to subscribe the product. Thus, we would like to build a classification machine learning model to help the bank identify the targeted group and improve campaign efficiency. (i.e.: classify if the customer will subscribe a term deposit or not based on explanatory features. Let bank change marketing strategy targets to the customer with predicted “yes” answer of subscription.)     

At the end of this project, we will select the best classification model with highest prediction accuracy score for subscription to help the bank marketing in the future.
When building the model, we would like to follow the steps:
1. Exploratory data analysis: have an overview and understand the dataset.   
2. Data Pre-processing: data cleaning, missing value imputation, categorical value encoding   
3. Modeling: Implement 2 machine learning models (SVM + MLP), hyperparameter tuning   
4. Evaluation: Since this is a classification problem, we will use Accuracy, Recall, Precision， confusion matrix, AUROC    

We implement 2 machine learning models for our binary classification problem.
One is support vector machine (SVM) classifier. It is commonly used in classification problems. In the SVM
algorithm, we plot each data item as a point in n-dimensional space (where n is a number of features)
with the value of each feature being the value of a particular coordinate. Then, we perform classification
by finding the hyper-plane that differentiates the two classes very well. SVM works more efficient in high
dimensional spaces. Therefore, we think it is suitable to use SVM classifier for our task. Check code for
more details.


Another is multi-layer perceptron(MLP) classifier. MLP classifier relies on an underlying neural network to
perform the task of classification. Its multiple layers and non-linear activation distinguish MLP from a linear
perceptron. It can distinguish data that is not linearly separable. Therefore, we think it is suitable to use MLP
classifier for our task.
