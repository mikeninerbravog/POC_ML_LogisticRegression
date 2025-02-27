# Logistic Regression - Proof of Concept (POC)

This repository presents a **Proof of Concept (POC)** for using **Logistic Regression**, a fundamental classification algorithm, to solve real-world problems. The POC includes two practical examples:

1. **Medical Diagnosis:** Predicting whether a patient has diabetes based on health-related factors.
2. **Spam Detection:** Classifying emails as spam or not based on textual and sender characteristics.

## 📌 **Project Objective**
Demonstrate how **Logistic Regression** can be applied to real-world classification problems, showing its ability to estimate probabilities and classify instances based on input features.

## 🔍 **What is Logistic Regression?**
Logistic Regression is a statistical model used for binary classification problems. Despite its name, it is not used for regression tasks but rather for answering questions like **"Yes or No?", "True or False?", "Spam or Not Spam?"**.

The algorithm works by estimating the **probability** of an instance belonging to a given category. If this probability is **greater than 50%**, the model assigns it to one class; otherwise, it assigns it to the other.

---
## **Example 1: Medical Diagnosis - Diabetes Prediction**
This model predicts whether a patient has diabetes based on:
- **Age**
- **Blood sugar level**
- **Blood pressure**
- **Family history** (whether the patient has relatives with diabetes)

Using these features, **Logistic Regression** calculates the probability of a patient having diabetes. If the probability is **greater than 50%**, the model classifies the patient as **"Yes, has diabetes"**; otherwise, it classifies as **"No, does not have diabetes"**.

---
## **Example 2: Spam Detection**
Spam filters in email services use **Logistic Regression** to classify messages as spam or not spam based on:
- **Keywords in the email** (e.g., "free", "click here", "special offer")
- **Number of suspicious links**
- **Sender reputation** (whether the sender has sent spam before)

The algorithm calculates the **probability** of an email being spam. If the probability exceeds **50%**, the email is classified as spam; otherwise, it is considered legitimate.

---
## 📂 **Project Structure**
The code is available in a Google Colab notebook:

[Open in Colab](https://colab.research.google.com/github/mikeninerbravog/POC_ML_LogisticRegression/blob/master/POC_ML_LogisticRegression.ipynb)

This notebook includes:
- Implementation of both examples (diabetes prediction and spam detection).
- Step-by-step explanation of Logistic Regression.
- Data preprocessing, model training, evaluation, and visualization.

## ⚙ **How to Run the Code**
You can execute the code directly in Google Colab without any local setup.

### **Steps to Run in Colab:**
1. Click on the **Open in Colab** link above.
2. Run each cell sequentially in the notebook.
3. Explore the predictions, accuracy reports, and visualizations.

## 📊 **Expected Results**
The notebook provides:
- **Individual predictions** for sample inputs.
- **Model accuracy** for both examples.
- **Confusion matrix** to analyze classification errors.
- **Classification report** (precision, recall, and F1-score).

## 📈 **Results Visualization**
The project generates **confusion matrix plots** to visualize the model's performance in classifying instances.

## 🚀 **Why Use Logistic Regression?**
✔ Simple and effective for binary classification problems.
✔ Provides interpretable probability-based predictions.
✔ Widely used in fields such as healthcare, cybersecurity, and finance.

## 📜 **License**
This project is licensed under the MIT License - see the `LICENSE` file for details.
