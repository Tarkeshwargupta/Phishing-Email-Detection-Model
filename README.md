# Phishing Email Detection Model

A machine learning-based cybersecurity project that detects whether an email is phishing or safe.

## Features

- Phishing and legitimate email classification
- TF-IDF text feature extraction
- URL feature extraction
- Suspicious keyword detection
- Logistic Regression classification
- Accuracy evaluation
- Precision, Recall and F1-score
- Confusion Matrix
- Real-time email prediction

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

## Project Structure

phishing-email-detector/
│
├── dataset/
│   └── emails.csv
│
├── model/
│   └── phishing_model.pkl
│
├── results/
│   └── confusion_matrix.png
│
├── src/
│   ├── train_model.py
│   └── predict_email.py
│
├── requirements.txt
├── README.md
└── .gitignore

## Machine Learning Pipeline

Email
↓
Text Cleaning
↓
TF-IDF Feature Extraction
↓
URL Feature Extraction
↓
Feature Combination
↓
Logistic Regression
↓
Phishing / Safe

## Model

The project uses Logistic Regression for binary classification.

Labels:

0 → Safe

1 → Phishing

## Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## How to Run

Install dependencies:

pip install -r requirements.txt

Train the model:

python src/train_model.py

Predict an email:

python src/predict_email.py

## Future Improvements

- Use a larger real-world dataset
- Add sender/domain reputation features
- Detect shortened URLs
- Analyze email headers
- Add a web interface
- Compare multiple machine learning algorithms
- Deploy the model as an API

## Author

Tarkeshwar Gupta

Cybersecurity Student
