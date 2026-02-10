# DATA_GENERATION_USING_MODELLING_AND_SIMULATION

## Overview
This project generates simulation-based data using **SimPy**, a Python discrete-event simulation library. The generated dataset is used to evaluate and compare multiple Machine Learning regression models.

Note- you can use any simulation library.

## Objective
- Simulate a real-world system using SimPy  
- Generate synthetic dataset using simulation  
- Apply multiple Machine Learning regression models  
- Compare model performance using evaluation metrics  

## Parameters Used

| Parameter | Description | Range |
|------------|----------------|-------------|
| Arrival Rate | Time interval between patients | 1 – 10 |
| Service Time | Treatment time per patient | 2 – 15 |
| Number of Servers | Number of doctors available | 1 – 5 |

## Machine Learning Models
- Linear Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Regressor  
- Random Forest Regressor  
- Support Vector Regressor (SVR)

## Installation
`pip install simpy pandas scikit-learn numpy matplotlib`

## Output 
- Model results
<img width="306" height="99" alt="image" src="https://github.com/user-attachments/assets/1f0ad01e-fe95-48e2-89d3-60d9c6c604e4" />
- Graph
<img width="436" height="411" alt="image" src="https://github.com/user-attachments/assets/ba46736c-891f-4668-8cf8-626bf34b1b45" />


