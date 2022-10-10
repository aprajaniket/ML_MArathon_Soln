# ML_MArathon_Soln
Predicting Whether The Customer Will Subscribe To Term Deposit         
1-Population Segmentation      
2-Customer's place    
3-Price    
4-Promotional Strategy                   

#Tools and Algorithms Used for Analysis            
Python 
Numpy 
Pandas 
Seaborn 
Logistic Regression 
Decision Tree Classifier

data.csv : Use this dataset to train the model. This file contains all the client and call details as well as the target variable “subscribed”. 
You have to train your model using this file.

test_data.csv : Use the trained model to predict whether a new set of clients will subscribe the term deposit.

#ANSWER FOR ML QUESTIONS
1. While attempting Problem 1 in the hackathon, which feature/features according to you
played the most important role in prediction of the deposit? Can you visualize the same
and which algorithm you used for determining that and why?

Answer - JOB was the main feature which help to find the solution

2. The data science team in your company is trying to build a classifier with a target having
two possibilities (yes/no) and what they are interested in is that the solution must be fast
enough to be used by the deployment team to predict for the new dataset. Which
algorithm do you suggest and why?

Answer -Logistic regression, it is easy and can create confusion matrix ,ROC and Cap curve

3. Suppose the data you used in building a model has a low variance and low bias. Can
you guess how the data will look like in the predicted outcome? Give a proper
explanation.

Answer -There is a tradeoff between a model’s ability to minimize bias and variance. 
Gaining a proper understanding of these errors would help us not only to build accurate 
models but also to avoid the mistake of overfitting and underfitting.

4. Suppose you have a dataset that has missing values, and you tried multiple
classification algorithms but you are not getting good results, which algorithm do you
recommend to the team and why?

Answer - Many machine learning algorithms fail if the dataset contains missing values. 
However, algorithms like K-nearest and Naive Bayes support data with missing values





