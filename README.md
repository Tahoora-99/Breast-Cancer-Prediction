# Breast-Cancer-Prediction
Logistic Regression Model for Breast Cancer Detection
This project utilizes Logistic Regression to predict cancer diagnoses using the Breast Cancer Dataset from Kaggle(https://www.kaggle.com/datasets/erdemtaha/cancer-data). The dataset contains 569 samples of cancerous cells, each characterized by 30 distinct features.
Accuracy: % 98 which means the overall probability that the model correctly identifies the class of any given sample. 

![image](https://github.com/user-attachments/assets/70e20228-9b3b-4b80-9a48-59620f37fc1f)


## 🧠 Mathematical Interpretation of the Table

To describe this table using mathematical notation, we can use conditional probabilities:

Precision (Class 1): The conditional probability that a person truly has cancer given the model-predicted cancer:
𝑃(Cancer∣Predicted Cancer)=0.98

Recall (Class 1): The conditional probability that the model predicts cancer given the person actually has cancer:
𝑃(Predicted Cancer∣Cancer)=0.98

Precision (Class 0): The conditional probability that a person is healthy given the model predicted healthy:
𝑃(Healthy∣Predicted Healthy)=0.99

Recall (Class 0): The conditional probability that the model predicts healthy given the person is actually healthy:
𝑃(Predicted Healthy∣Healthy)=0.99
This model demonstrates a strong focus on minimizing false negatives, ensuring that patients who may have cancer are less likely to be overlooked.

