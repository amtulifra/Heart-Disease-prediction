# Heart-Disease-prediction

Heart disease is a term covering any disorder of the heart. Heart diseases have become a major concern to deal with as studies show that the number of deaths due to heart diseases have increased significantly over the past few decades in India, in fact it has become the leading cause of death in India.

A study shows that from 1990 to 2016 the death rate due to heart diseases have increased around 34 per cent from 155.7 to 209.1 deaths per one lakh population in India.

Thus preventing Heart diseases has become more than necessary. Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives. This is where Machine Learning comes into play. Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.

Dataset :
The dataset consists of 303 individuals data with 14 columns 

The 14 attributes are:

  1.age
  
  2.sex
  
  3.chest pain type (4 values)
  
  4.resting blood pressure
  
  5.serum cholestoral in mg/dl
  
  6.fasting blood sugar > 120 mg/dl
  
  7.resting electrocardiographic results (values 0,1,2)
  
  8.maximum heart rate achieved
  
  9.exercise induced angina
  
  10.oldpeak = ST depression induced by exercise relative to rest
  
  11.the slope of the peak exercise ST segment
  
  12.number of major vessels (0-3) colored by flourosopy
  
  13.thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
  
  14.target:0-->healthy heart , 1 ---> defective heart
  

Model Training and Prediction :

We can train our prediction model by analyzing existing data because we already know whether each patient has heart disease. This process is also known as supervised learning. The trained model is then used to predict if a person suffer from heart disease. The training and prediction process is described as follows:

1.Splitting:
First, data is divided into two parts using component splitting. Here,the data is split based on a ratio of 80:20 for the training set and the testing set.The model is then fitted using the training data and tested on the unseen test data.A logistic regression model is used while training the data.After building the model,the accuracy score for training data set is 85% and testing dataset is 81.96%

2.Prediction:
The model now predicts whether a person has a heart disease or not based on the input values provided.If the  predicted value is 0 then it  prints a message saying 'This person does not have a heart disease' else it prints 'The person has heart disease'.
