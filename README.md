# Exoplanet Exploration

A planet-hunting mission is to discover hidden planets outside of our solar system. 3 machine learning models are created to classify candidate exoplanets based on raw dataset.

1. Preprocess the data:


Drop unnecessary rows and columns.


Use MinMaxScaler to scale the numerical data.



Seperate the data into training and testing data.





   2. Select Model and Tune Model



Logistic Regression model was used to classify the data. The training data score is 0.85 and the testing data score is around 0.84.




KNeighborsClassifier was also used to classify the data. When k=51, the train/test score is around 0.83.




Support Vector machines was also used to classify the data. The training score is around 0.85 and the testing score is around 0.84. After tuning the model's parameters, the best score of 0.89 was got when C=100 and gamma=0.00005.
