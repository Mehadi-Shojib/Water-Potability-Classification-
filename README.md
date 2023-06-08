# Water-Potability-Classification Using Python

Library used: pandas,seaborn,matplotlib,numpy,sklearn

Data Source: This data set is taken from Kaggle.com. The name of the dataset is Water Quality Prediction. The art of water quality prediction has been a difficult task for many of the researchers and analysts. It’s very important to predict water for drinking safely. So, we decided to predict water quality using data set which is downloaded from Kaggle to train our model and evaluate by testing using 10 attributes. We are going to predict 2 types of water potability conditions (potable or not potable). 

Dataset Link:
url: https://www.kaggle.com/datasets/adityakadiwal/water-potability

Description of Dataset:
I have used a dataset about weather information from Kaggle to train our model and evaluate by testing.
Number of Instances: 3276
Number of Attributes: 10 numeric predictive.


I developed 5 different classifier models which are Gaussian Naive Bayes, K Nearest Neighbors (KNN), Decision Tree, Logistic Regression and Support Vector Machine. The lowest accuracy model is which accuracy is 0.5518 and the highest accuracy is 0.6021 and 0.6006. The Decision Tree (DT) and Gaussian Naive Bayes (NB) model gives us the maximum accuracy and K Nearest Neighbors (KNN) model gives us the lowest accuracy. Logistic Regression (LR) and Support Vector Machine (SVM) models are given the same accuracy which are 0.5686. As a result, it can be said that the Decision Tree (DT) and Gaussian Naive Bayes (NB) classifier are the best use for this dataset model. The Decision Tree (DT) and Gaussian Naive Bayes classifier model's accuracy is below 70% because of the dataset. It might perform better if we can train this model on a larger dataset.
So, in my opinion, depending on this dataset, the Decision Tree (DT) and Gaussian Naive Bayes classifier is much better for predicting the water potability. Although, for a larger dataset other models may perform better.
