# **Lending-Loan-Kaggle**
This data set represents thousands of loans made through the Lending Club platform, which is a platform that allows individuals to lend to other individuals. This data set only represents loans actually made, i.e. do not mistake this data for loan applications! We will be using a subset of the LendingClub DataSet obtained from Kaggle

funded_amnt:That point in time.

emp_length:Number of years in the job, rounded down. If longer than 10 years, then this is represented by the value 10.

annual_inc:The self-reported annual income provided by the borrower during registration. 

home_ownership:The home ownership status provided by the borrower during registration or obtained from the credit report. Our values are: RENT, OWN, MORTGAGE, OTHER

grade:LC assigned loan grade

mort_acc:Number of mortgage accounts.

pub_rec: Number of derogatory public records

int_rate:Interest Rate on the loan

open_acc:The number of open credit lines in the borrower's credit file.

num_actv_rev_tl:Number of currently active revolving trades.

mo_sin_rcnt_rev_tl_op:Months since the most recent revolving account opened.

mo_sin_old_rev_tl_op:Months since oldest revolving account opened.

bc_util:High credit/credit limit for all bankcard accounts.

bc_open_to_buy:Total open to buy on revolving bank cards.

avg_cur_bal:Average current balance of all accounts.

acc_open_past_24mths:Number of trades opened in the past 24 months.

Data Source: https://www.kaggle.com/wordsforthewise/lending-club

# **Model Overview**

We build 2 models: Logistic Regression and Random Forest

*Logistic Regression*: is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression[1] (or logit regression) is estimating the parameters of a logistic model (a form of binary regression).

*Random Forest*: Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes (classification) or mean/average prediction (regression) of the individual trees. Random decision forests correct for decision trees' habit of overfitting to their training set. Random forests generally outperform decision trees, but their accuracy is lower than gradient boosted trees. However, data characteristics can affect their performance. 

# **Model Accuracies**

Accuracy of Logistic Regression: 80.55

Accuracy of RandomForestClassifier: 80.58
