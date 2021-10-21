# Company_Bankruptcy_prediction_Classification_usecase

Estimating the risk of corporate bankruptcies is of large importance to creditors and investors. There are large indirect and direct costs associated with financial distress and Corporate bankruptcies can have serious effects both locally and globally on employees, investors, customers, suppliers and their financiers are all affected when a company disappears in some cases a corporate bankruptcy can cause an entire industry to suffer.

Machine learning models have successfully been used for many classification and regression problems and these models have often outperform traditional classification methods. The purpose of bankruptcy prediction is to predict future perspectives of a company. For a given period, this problem can be modelled as a two-class classification problem. Companies either survive the given time period or go bankrupt during it. The problem is to predict which of these two possible outcomes that is the more probable one.

Through the project I have performed the followings,
* visualising the dataset of target variable(Bankrupt) using EDA.
* Checking Multicollinearity relationship between Independent Variables, removing them if any variable is strongly correlated with another.
* Feature selection
* Applied SMOTE oversampling technique to overcome class imbalance.
* Applied MinMax Scaler transformation to make same units on data.
* Then applied the below models, and selecting which model produces a good Recall score.
    * Logistic Regression
    * Decision Trees
    * K nearest neighbor
    * XGBoost Classifier
    * Random Forest
    * Support Vector Machine and
    * Artificial Neural Network


Logistic Regression model performed well among other models and along with Cross Validation, this model predicts 85% Recall score.

