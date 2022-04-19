# BREAST CANCER PREDICTION USING FEEDFORWARD NEURAL NETWORK

## 1. Summary
#### * To create a accurate deep learning model
#### * To predict breast cancer using [Wisconsin Breast Cancer Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

## 2. IDE and Framework
#### * This project is done using google colaboratory
#### * There main framework involves in this project are Pandas,Scikit-learn and TensorFlow Keras.

## 3. Methodology
### 3.1 Data Pipeline
#### *The data is loaded and preprocessed ( removed unwanted features & label is encoded in one-hot format)
#### *The data is split into train-validation-test sets, with ratio of 60:20:20

### 3.2 Model Pipeline
#### *Since this is classification problem, a feedforward neural network will be used
#### *Figure below shows the structure of the model

![image](https://user-images.githubusercontent.com/103733709/163706793-947c7da7-3783-4f62-ac88-93e95342a6a0.png)

## 4.Results
#### *The model is trained with a batch size of 32 and for 100 epochs
#### *The model has achieved 92% in validation accuracy and 90.32% in training accuracy

![image](https://user-images.githubusercontent.com/103733709/163707765-23b53945-eb3a-4696-b2b1-d97ada5b445d.png)

#### *Figure belows shows the tests results
![image](https://user-images.githubusercontent.com/103733709/163707865-4191e8a7-8d54-44da-84a0-cd3eb6fe916a.png)




