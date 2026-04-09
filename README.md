# ANFIS Student Performance Prediction

## Overview
This project implements an Adaptive Neuro-Fuzzy Inference System (ANFIS) to predict student performance based on academic inputs.


## Inputs
- Attendance
- Assignment Marks
- Test Marks


## Output
- Performance Score
- Performance Level (Poor / Average / Good)


## Methodology
- Dataset of 1000 students used
- Data normalized
- Train-test split (80-20)
- ANFIS model trained with validation
- Early stopping used to prevent overfitting


## Results
- Training RMSE = 0.0311324  
- Checking RMSE = 0.0323606  
- Best Epoch = 1  
- Final Test RMSE ≈ 3.24  


## Sample Output
Predicted Score = 80  
Performance Level = Good  


## Screenshots

### Training Graph
![Training](screenshots/q2_training_vs_testing_error.png)

### Training Process
![Process](screenshots/q2_training_process.png)

### Output
![Output](screenshots/q2_final_output.png)


## Dataset
[View Dataset](dataset/student_performance_1000.xlsx)


## Report
[View Report](report/Q2_Report.pdf)


## Tools Used
- MATLAB
- ANFIS


## Author
Sumit Gareri
