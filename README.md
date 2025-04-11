## Overview

The primary goal is to predict whether individuals using e-cigarettes to quit smoking will be successful compared to those using traditional methods. The secondary goal is to assess whether those using vaping to quit smoking may develop an addiction to e-cigarettes.

---

## Data Used

The data for this analysis was collected from reliable sources such as:

- **National Center for Health Statistics (NCHS)**
- **Centers for Disease Control and Prevention (CDC)**

The dataset includes the following key features:
- **Demographic Information:** age, sex, health status, anxiety, and fatigue levels.
- **Smoking Habits:** age of first smoking, current smoking status, e-cigarette use, and average number of cigarettes smoked per day.
- **Healthcare Interaction:** advice given for smoking cessation.

The data analyzed spans from **2020 to 2021**, and the main challenge faced was dealing with a **imbalanced dataset**.

---

## Model Used

To address the problem, we used a **Random Forest** model, a robust method for binary classification that performs well with noisy data. The model is used for:

- **Predicting the likelihood of success** in quitting smoking with e-cigarettes.
- **Estimating the risk** of developing an addiction to e-cigarettes.

### Model Optimization:
To tackle the issue of imbalanced classes, we employed **SMOTE (Synthetic Minority Over-sampling Technique)**, which significantly improved the model's performance.

![BA](https://github.com/user-attachments/assets/97d6e2b0-a6ca-4d93-a885-3295b84eeaaf)

---

## Results

### Model Prediction Accuracy

![BA1](https://github.com/user-attachments/assets/d13770d0-d422-4d03-9139-cfc896f9ea2c)

- **Initial Model Accuracy:** 70%
- **Improvements with SMOTE:**
  - **Accuracy improved to 86%.**
  - **Error rate reduction:** 
    - From **26.5% to 19.7%** for those who quit smoking.
    - From **5.3% to 3.9%** for those who continued smoking.

---

## Conclusions

The findings suggest that E-cigarettes do not appear to be an effective tool for quitting smoking.

![BA2](https://github.com/user-attachments/assets/200d5bed-6944-4322-8e7b-f91ce37d0091)
