# Student Task Feedback Prediction

This project involves building machine learning models to predict:
1. Whether students are **satisfied** with the task prompts.
2. Whether students would **use the prompts again**.

## 📂 Dataset
The dataset includes:
- Task discipline and type
- Number of prompts given
- Satisfaction rating
- Whether the student would use the prompt again

## 🔍 Objectives
- Predict `satisfied` (binary classification)
- Predict `UsedAgain` (binary classification)
- Analyze feature importance and improve model performance

## 🛠️ Features Used
- `Discipline`
- `TaskType`
- `TotalPrompts`
- `SatisfactionRating`

## 📊 Models Applied
- Logistic Regression
- Random Forest Classifier
- Feature importance via ExtraTreesClassifier

## 📈 Evaluation
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

## 🧪 Requirements
Install the required Python packages using:

```bash
pip install -r requirements.txt
