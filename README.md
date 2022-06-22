# ProductivityPrediction
## 1. Summary
The Garment Industry is one of the key examples of the industrial globalization of this modern era. It is a highly labour-intensive industry with lots of manual processes. Satisfying the huge global demand for garment products is mostly dependent on the production and delivery performance of the employees in the garment manufacturing companies. So, it is highly desirable among the decision makers in the garments industry to track, analyse and predict the productivity performance of the working teams in their factories.The aim of this project is to create a regression deep learning model to predict the productivity of employees. The model is trained with [Garments Worker Productivity Data](https://archive.ics.uci.edu/ml/datasets/Productivity+Prediction+of+Garment+Employees).

## 2. IDE and Framework
This project is created using Google Colab as the main IDE. The main frameworks used in this project are Pandas, Scikit-learn and TensorFlow Keras.

## 3. Methodology
### 3.1. Data Pipeline
The data is loaded to Google Colab and preprocessed.There are a few missing values in wip(work in progress) column There are no missing values in the data and label is encoded in one-hot format. This dataset can be used for regression purpose by predicting the productivity range (0-1) or for classification purpose by transforming the productivity range (0-1) into different classes.

### 3.2. Model Pipeline
The structure of the model is fairly simple. Figure below shows the structure of the model. There are 2 layers and 1 output layer.

![image](https://user-images.githubusercontent.com/63838426/175105722-e04c5a24-a415-4300-81ae-18ebbc8c485a.png)
## 4. Results

Below are the result of the training

![image](https://user-images.githubusercontent.com/63838426/175105693-73ff7e88-d293-4bf4-919e-0542824c4044.png)

![image](https://user-images.githubusercontent.com/63838426/175105709-98d32452-e5da-4d7e-b25f-86b479d50ecb.png)


