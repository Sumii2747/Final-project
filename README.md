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

# Speed Calculation 
![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/50e9157c-96a0-4a91-a6e6-8e93b1f73aa2)
Where v = final speed
	u = initial speed
	a= acceleration
	t = time at any moment during motion

# Data Cleaning and Transformation
![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/be0f7762-a585-4d5f-ac25-8b68b3600e15)

![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/8945d510-c5cb-4056-bcf7-d8a3cbb3494b)

# Machine Learning models
Machine learning models to be utilized include - Random Forest, K-Nearest Neighbours, and Support Vector Machine (SVM). 
Random Forest was considered as it can handle large datasets like the NGSIM data with high-dimensional features and is relatively less sensitive to irrelevant features.
KNN and SVM will help to produce a simple and intuitive algorithm used for classification and regression tasks
•	The equation of motion was then passed into a loop which was then used to calculate the corresponding speed and intervehicle spacing for different reaction times (0.5, 1, 1.5, 2 seconds).
•	The model was then used to determine the r2_score, and root mean square error for each reaction time (0.5, 1, 1.5, 2 seconds).

# Results
The study successfully developed predictive models for acceleration using Random Forest (RF), K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) algorithms. The models utilized the equation of motion to calculate speed and intervehicle distance. By analyzing the data, the models predicted the acceleration for the next time frame. The study found that RF outperformed both KNN and SVM in terms of predictive accuracy for velocity and spacing. However, RF showed the most significant improvements, especially at the 0.5-second reaction time mark. This indicates RF's proficiency in capturing underlying patterns related to short reaction times. Additionally, the analysis revealed that as the reaction time increased, the R2_score reduced for all the models. 

![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/6ae0d411-67a2-476d-9e5b-f8fa530a2ec4)
![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/a2270ee8-a615-4c02-b98e-4ecce3112282)


![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/3382410a-33f2-4dbd-ac3f-304fa4a817b1)
![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/aaa94810-a3de-4741-8dee-4b0c0b8ec747)
![image](https://github.com/gracedtope/Car-Following-Model-Speed-Prediction/assets/105440600/983e0e52-69c5-4daf-97c1-f0cc3b7855ce)











