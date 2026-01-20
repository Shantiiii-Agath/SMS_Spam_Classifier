# SMS Spam Classifier using Machine Learning

## Problem Statement

The objective of this project is to classify SMS messages as **Spam** or **Not Spam (Ham)** using machine learning techniques. This helps in filtering unwanted or malicious messages automatically.

---

## Dataset Description

The dataset consists of SMS messages labeled as:

* **Spam** – Unwanted or promotional messages
* **Ham** – Legitimate messages

Each message is a text string, and the target variable is the message category.

---

## Machine Learning Workflow

1. Data loading and text exploration
2. Text preprocessing (lowercasing, cleaning)
3. Feature extraction using **TF-IDF Vectorizer**
4. Train-test split
5. Model training using a classification algorithm
6. Model evaluation using classification metrics

---

## Model Used

* **Machine Learning Classification Model**

TF-IDF was used to convert text data into numerical features so that machine learning algorithms can process SMS messages effectively.

---

## Evaluation Metrics

The model performance was evaluated using:

* **Accuracy** – Overall correctness of predictions
* **Precision** – Important for minimizing false spam detection

These metrics ensure that genuine messages are not incorrectly classified as spam.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP) techniques

---

## 📌 Conclusion

This project demonstrates an end-to-end NLP-based text classification pipeline, including text preprocessing, feature extraction, model training, and evaluation. It showcases practical application of machine learning for real-world spam detection problems.

