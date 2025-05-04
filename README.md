# Viewer Propensity Project


Project Description:-

Database Name: Advertising.csv

Nutshell: The project consists of the nutshell of the model, which has been constructed using Visio.

Database Source: https://www.kaggle.com/code/mafrojaakter/customer-ad-click-prediction
 
Database Description: The database consists of details about the number of people who clicked on ads or not, which has been signified in the form of binary classified language 0 and 1. (0 = Not click & 1= Click)
 
Project Objective: The project aims to build a predictive model that aims to forecast the probability of whether people will click on ads or not.

Impact: There are 90% true cases being predicted under the model.

Process:
The model follows 5 steps:-

 a) Database Acquisition:
    After the data was extracted from Kaggle in a CSV format, it was uploaded to Jupyter Notebook using the Pandas library. 

 b) EDA (Exploratory Data Analysis):
    The project consists of data visualization using Matplot and Seaborn Library. The graphs are:-
    
    1) Histogram: Frequency distribution of age among the users.

    2) Jointplot: 

       i) Income V/S Age

       ii) Daily Spent V/S Age (Hue= Clicked on Ad)

       iii) Daily time spent V/S Daily internet usage

    3) Pairplot


 c) Database Training & Testing:

      i) Testing Dataset: 30% of the database.
      ii) Training Dataset: 70% of the database.

 d) Model Testing:

      i) Classification Report:
      
           - Precision score:  90 
           
           - Recall Score: 90

      ii) Confusion Matrix:

           - Accuracy = (True Negative + True Positive)/Total cases  = 140 + 129 = 269/300 = 90% 

  e) Model Deployment:

       -The model has been deployed on the testing dataset with the capability of predicting the outcome with an accuracy of 90%. 

       -Using Sigmoid Activation function, the model's accuracy has been increased to 97.74%.
      
       -The prediction on the Model shows that the chances for the user to click on ads are higher. 

        
    

       
