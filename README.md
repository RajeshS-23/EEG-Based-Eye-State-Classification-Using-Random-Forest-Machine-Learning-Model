# EEG Eye State Classification using Random Forest

This project focuses on classifying eye states (open or closed) using EEG
signal data and a Random Forest machine learning model. The goal is to build
a reliable classifier by learning patterns from EEG features.

---

## Project Description

EEG-based eye state detection is useful in applications such as attention
monitoring, fatigue detection, and brain–computer interface systems.
In this project, a Random Forest classifier is trained on EEG data to
predict whether the eyes are open or closed.

---

## Dataset Information

- Dataset: EEG Eye State Classification
- Target column: eyeDetection
  - 0 – Eyes Open
  - 1 – Eyes Closed
- Input features: EEG signal attributes
- Dataset location: `dataset/EEG_Eye_State_Classification.csv`

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Methodology

1. Load the EEG dataset
2. Perform basic data inspection
3. Split the data into training and testing sets
4. Train a Random Forest classifier
5. Evaluate model performance
6. Visualize feature importance

---

## Model Details

- Algorithm: Random Forest Classifier
- Number of trees: 400
- Maximum depth: 30
- Train–test split: 80:20

---

## Results

The model provides good classification accuracy on unseen test data.
Feature importance analysis shows which EEG signals contribute most to
the eye state prediction.

---

## How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/EEG-Eye-State-Classification.git
