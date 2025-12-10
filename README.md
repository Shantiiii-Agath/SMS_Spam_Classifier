# SMS Spam Classifier

This project classifies SMS messages as Spam or Ham using a Naive Bayes model.

## Dataset
- SMS Spam Collection dataset (`sms_spam.csv`)

## Steps
1. Load dataset
2. Preprocess text (lowercase, remove stopwords)
3. Convert text to numeric features using TF-IDF
4. Split data into train/test
5. Train Naive Bayes classifier
6. Evaluate using Accuracy, Precision, Recall, F1

## Libraries
- Python
- pandas
- scikit-learn

## How to Run
1. Open SMS_Spam_Classifier.ipynb in Jupyter Notebook or Colab
2. Run all cells
3. View accuracy, classification report, and make new predictions

## Optional Improvements
- Try Logistic Regression
- Add more preprocessing
- Compare models
