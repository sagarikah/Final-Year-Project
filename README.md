# Final Year Project
## Objective
This project report makes an analysis of the effects that QoS impairments such as delay, jitter and packet loss have in the quality of VoIP calls. We will use Machine Learning approach to solve this problem by developing a Machine Learning model which optimizes QoS parameters to enhance the quality of VoIP calls.

## Simulation
- QoS dataset is generated which consists of 204 samples and 8 VoIP traffic parameters- packet loss rate, jitter, delay, a, effective delay, R, final R and Mean Opinion Score (MOS). 
- Data pre-processing is performed by removing the redundant features and scaling the features. 
- Dataset is splitted into training and test sets.
- The training data is applied to 5 ML algorithms – Linear Regression, KNN, Decision Tree, Gradient Descent and Voting Ensemble to construct the models. 
- The models were validated and their performances were compared. 
- Finally, we predicted the MOS values based on the optimal machine learning model. 

![image](https://user-images.githubusercontent.com/76590161/169748827-5f95d629-b45c-4e19-849c-2c7e27d2906b.png)
