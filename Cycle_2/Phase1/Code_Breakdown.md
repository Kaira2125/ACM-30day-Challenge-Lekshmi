# **BREAST CANCER DATASET - PHASE 1**
- I started by importing essential libraries.
- Followed by uploading the dataset which contained medical information about tumors and their other attributes.
## **Data Preprocessing**
Before training the models, I cleaned the dataset.
- Removed irrelevant columns like Patient ID.
- Converted the diagnosis column from labels M for malignant to 1(binary values) and B for Benign.
## **Splitting Features and Labels**
I separated the dataset into:
-Features (X) – the input variables that help make predictions.
-Labels (y) – the target variable (diagnosis) we aim to predict.
## **Train-Test split**
The dataset was split into training and testing sets.
- Training data is used to build the model.
- Testing data is used to evaluate how well the model generalizes to unseen data.
## **Training the models**
After that I trained:
- Random Forest Classifier (Bagging)
- AdaBoost Classifier (Boosting)
- XGBoost Classifier (Boosting)
## **Model Evaluation**
After training each model, I evaluated their performance using:
- Accuracy Score – to see the percentage of correct predictions.
- Confusion Matrix – to understand how well the model predicts each class (malignant vs. benign).
# **Result**
Random Forest	95.61%
AdaBoost	97.37% 
XGBoost	95.61%
