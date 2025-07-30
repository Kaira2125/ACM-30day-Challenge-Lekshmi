# **Model Validation & Selection - Phase 5**
## **Importing Libraries**
We start by importing libraries like matplotlib, numpy, and sklearn. The data I decided to use was the dataset from the first phase 
## **Preparing the Data**
We load our dataset and split it into:
- Features (X) – the inputs the model learns from.
- Labels (y) – the actual categories or outputs.
## **Building the Random Forest**
- We use a Random Forest Classifier, which is made of many decision trees working together. 
- We train this classifier using the training data.
## **Plotting the Results**
We plot a graph:
- X-axis: Number of training samples.
- Y-axis: Accuracy score.
- Blue line: Training accuracy.
- Green line: Validation accuracy.
##**What Does the Graph Tell Us?**
- The model is not underfitting.
- There’s slight overfitting, but it's not harmful.
- Overall, the model is performing very well.
