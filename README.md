## <u>Flight_Prediction_Project:</u>


In this project I am predicting Flight Fare of tickets based on some previous months data and make an app and deploy it on Netlify cloud platform.

## <u>Problem Statement:</u>
 
Travelling through flights has become an integral part of today’s lifestyle as more and more people are opting for faster travelling options.The flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, and duration of flights various occasions such as vacations or festive season. Therefore, having some basic idea of the flight fares before planningthe trip will surely help many people save money and time.

## <u>Goal:</u>

The goal is to predict the fares of the flights based on different factors available in the provided dataset.

## <u>Approach:</u>
The classical machine learning tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and Model Testing. Try out different machine learning algorithms that best fits for the above case.

## <u>Model Selection:</u>

I have use RandomForest Regression:

1.In RandomForest i have get Training Score as 95% whereas i have got Testing Score only 83% which is a sign of Overfitting.

2.In RandomForest i have got 83% of R2 score.

## <u>HyperParmeter Tuning:</u>

Use the Hyper-Parameter Tuning to achive the model accuracy good in nature.
Uses RandomSearchCV and get a Training and Testing Score 78.98% and 78.29% which is a good sign of a model.
I want to use GridSearchCV but i have a very low processor so it is taking very very much time so,i left it.
After that i have save the model in pkl file so that i can use it in PyCharm for making app.

## <u>Deployment Link:</u>
