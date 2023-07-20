# Car-Following-Model-Speed-Prediction
Speed prediction in a car following model using machine learning models
Car-following models were first introduced in the 1950s to analyze the kinematic relationship between consecutive vehicles along one travel lane without overtaking maneuvers. Car-following models are essential tools for traffic engineers, urban planners, and researchers to analyze and improve traffic flow, safety, and overall transportation efficiency in both existing and future road networks.


![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/5920464e-4f44-4750-a0d8-619a8a44dc4f)

# Objectives
1. Predict the Acceleration using the machine learning models
2. Predict the corresponding speed and intervehicle distance between the lead and subject vehicles

# Dataset
The dataset used in this project is called the Next Generation Simulation (NGSIM) and is publicly available on the US Department of Transportation website. The utilization of this dataset remains prevalent in transportation research, particularly for examining and modeling traffic flow, estimating and predicting traffic-related factors, and studying vehicular ad hoc networks. 
This repository contains the NGSIM Cleaned Dataset, a cleaned and preprocessed version of the Next Generation Simulation (NGSIM) dataset for traffic flow analysis. The NGSIM dataset provides detailed vehicle trajectory data collected on highways in the United States. (https://github.com/Shuoxuan/NGSIM_Cleaned_Dataset)

![car](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/d1bd5a44-93c4-417f-bef9-f7ba0bdc56f9)
This project utilize machine learning models and the Laws of motion to predict Acceleration, Speed, and intervehicle distance.

# Machine Learning models
Machine learning models to be utilized include - Random Forest, K-Nearest Neighbours, and Support Vector Machine (SVM). 
Random Forest was considered as it can handle large datasets like the NGSIM data with high-dimensional features and is relatively less sensitive to irrelevant features.
KNN and SVM will help to produce a simple and intuitive algorithm used for classification and regression tasks

# Speed Calculation 
Speed = Acceleration/time


