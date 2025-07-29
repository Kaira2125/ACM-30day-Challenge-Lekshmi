# **CREDIT CARD FRAUD DETECTION – PHASE 2**
- I started by importing essential libraries.
- Followed by uploading the dataset which contained transaction data labeled as fraudulent or non-fraudulent.

## **Data Preprocessing**  
The dataset was highly imbalanced, with very few fraud cases and so I used **undersampling** to select an equal number of non-fraud and fraud cases to ensure fair training.

## **Feature Preparation**
- Dropped the Time column (not useful for prediction).
- Separated the features (X) and the labels (y).
- Used StandardScaler to normalize the features for better model performance.

## **Train-Test Split** 
- Split the balanced dataset into **training** and **testing** sets.  
- Training data helps the model learn patterns.  
- Testing data checks how well it generalizes to unseen transactions.

## **Training the Models**
I trained three different Support Vector Machine (SVM) models using different kernel functions.
- Linear Kernel
- RBF Kernel  
- Polynomial Kernel

## **Model Evaluation**
For each model, I evaluated performance using:
- Accuracy Score
- Confusion Matrix
- PCA Visualization

# **Results**
- Linear Kernel: 95.93%
- RBF Kernel: 92.82%
- Polynomial Kernel: 90.35%
