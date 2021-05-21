# **Lending Loan Kaggle**
This data set represents thousands of loans made through the Lending Club platform, which is a platform that allows individuals to lend to other individuals. This data set only represents loans actually made, i.e. do not mistake this data for loan applications! We will be using a subset of the LendingClub DataSet obtained from Kaggle

Data Source: https://www.kaggle.com/wordsforthewise/lending-club

# **Model Overview**

We build 2 models: Logistic Regression and Random Forest

*Logistic Regression*: Logistic Regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression (or logit regression) is estimating the parameters of a logistic model (a form of binary regression).

*Random Forest*: Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes (classification) or mean/average prediction (regression) of the individual trees. Random decision forests correct for decision trees' habit of overfitting to their training set. Random forests generally outperform decision trees, but their accuracy is lower than gradient boosted trees. However, data characteristics can affect their performance. 

# **Model Accuracies**

Model | Accuracy
--- | ---
Logistic Regression with Grid search CV            | 80.55
Random Forest with Randomized search CV            | 80.58
