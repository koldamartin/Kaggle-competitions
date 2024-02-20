# Kaggle-competitions
These are my notebooks from Kaggle competitions. Kaggle is a data science competition platform. The same notebooks can be seen on the kaggle site as well https://www.kaggle.com/martinkolda/code
All the models are trained on tabular data from train.csv files. The task is to predict unlabeled data on test.csv.


1. Titanic - Machine learning from Disaster - I use LazyPredict library to quickly find out the best performing algorithm. In this case it is Support Vector Classifier

2. House Prices - Advanced Regression Techniques. I use Linear regression model to fill missing values in the LotFrontage feature. Then I use CatBoost algorithm and find the best hyperparameters with Optuna.

3. Multi-Class Prediction of Cirrhosis Outcomes - I use simple Artificial neural network model with no hidden layers. 

4. Binary Classification with a Bank Churn Dataset - Multiple boosted trees algorithms are tested. (LGBM, XGBRF, CatBoost, AdaBoost) Then one of the models with best ROC AUC score is chosen.

5. Natural language processing with Disaster tweets - Binary classification NLP task. I use a HuggingFace BERT model and then fine tune it on labeled data using Keras.
