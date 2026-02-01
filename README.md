# Naviotech_Project2_Titanic_Survival_Predictor_Dataset_Analysis_Project
Titanic was the famous ship which sank in 1912 during its first journey after an iceberg hit. It was the biggest ship of its time. 

How can we make the prediction of whether which passengers had survived after the hit and who were not able to survive. 
This repository consist of the  Naviotech Project 2 where the analysis of the famous Titanic Dataset has been made and also a  Streamlit UI Predictor has been made  which is easily usable by the users. 

In this project, I've used the Famous Titanic Dataset imported from Kaggle and I've done the analysis of the whole datset and also made a Streamlit UI Predictor, deployed on Streamlit Cloud Community. 

The algorith I used was the Random Forest Classification Algorithm which uses the Decision Trees to merge the outcomes and make predictions based on them. 

# Model Accuracy : 0.80 (80%)  

The predictions here are made mainly on 6 parameters:
   1.Passenger Class 
   
   2.Sex 
   
   3.Siblings / Spouses Aboard (SibSp) 
   
   4.Parents / Children Aboard (Parch) 
   
   5.Age 
   
   6.Fare  

In the dataset Analysis, I also used the Embarked parameter, but removed it from the UI Predictor as it holds very less importance in prediction and increases the user's difficulty. 

I've also made the visualization of the project easy by making various plots like: 
  
  1. Histogram
  2. Correlation Heatmap
  3. Confusion Matrix
  4. Countplot

Streamlit Ui Predictor Link : https://cmangla-titanic-survival-predictor.streamlit.app/
