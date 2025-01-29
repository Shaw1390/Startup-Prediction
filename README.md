# Startup Success Prediction using Machine Learning

This project uses machine learning to predict the success of startup companies based on various features such as funding, location, industry, and team size. The goal is to help investors and entrepreneurs make more informed decisions about which startups to invest in or launch or the startup will be successfull or not.




## DataSet

The dataset used in this project is sourced from crunchbase.com . It contains information about several thousand startup companies, including their funding history, location, industry, team size, and other relevant features. The dataset requires cleaning and preprocessing to remove missing values and outliers, and to convert categorical variables into numeric ones.
## Machine Learning Models

To predict the success of startups, we tested several machine learning models, including XGBoost Classifier(XBC), AdaBoost Classifier(ABC) , Random Forest Classifier (RFC), and Gradient Boosting Classifier (GBC). For each model, we performed a grid search to find the optimal hyperparameters that maximize the accuracy of the model.
## Results

After testing all the models, we found that Random Forest Classifier (RFC) gave the best accuracy score of 0.85. We also created a scatterplot of the feature importances of each model, which shows that funding and industry are the most important predictors of startup success.
## Model Deployment using Flask and Heroku

Created web app through Flask and deployed on heroku.

![alt text](https://github.com/Shaw1390/Startup-Prediction/blob/main/static/img/Screenshot%202025-01-21%20213114.png)

Link: https://starup-prediction-4998fe18888c.herokuapp.com/

### ----- Important Note -----
If the webapp is not working and you get the message as shown in the picture given below, it is occuring just because free dynos for this particular month provided by Heroku have been completely used. You can access the webpage on 1st of the next month.
