# CreditDefaulters



##### https://creditdefaulters22.herokuapp.com/

# creditCardDefaulters
The information of customers for last 6 months bill and payment are given. The goal is to build a machine learning model which
predicts whether a customer will default the nex payment or not.
 <br>There are two classes: 1 and 0. 
*	1 means that the customer will default the next month payment.
*	0 means customer is loyal .

Models Used here are **Naive Bayes and XGBoost**

#### Project Flow 
➡️ Data Collection from the Client (➡Data Description)
➡️ Data Validation 
➡️ Data Preprocessing and EDA
➡️ Data Clustering
➡️ Model & parameter tuning
➡️ Model Prediction
➡️ Deployment



## Instructions to run

 *Prerequisite*
 >IDE : Pycharm 

After cloning the repository<br>
install the requirements.txt
~~~python
 pip install requirements.txt
~~~

open http://localhost:5000/train to start training the model

After successful training 

open http://localhost:5000/prediction
<br>In the prediction page either you can check default predictions or  enter the path of the prediction files for custom prediction

#### Prediction page looks like this.

![alt Prediction Page](https://github.com/ramsahani/creditCardDefaulters/blob/main/Capture.JPG?raw=true)
