# SSIM916_Machine-Learning_Problem-Set_2

# Emotion Classification using Machine Learning

## 📌 Overview
This project investigates how effectively emotions can be classified from short text using transformer-based embeddings and supervised machine learning models.

## 📊 Dataset
- Source: HuggingFace Emotion Dataset
- Size: ~130,000 text samples
- Task: Multi-class emotion classification

## ⚙️ Methods Used
- Sentence-BERT (SBERT) embeddings
- Logistic Regression (with hyperparameter tuning)
- Neural Network (MLPClassifier)

## 📈 Evaluation
- Accuracy
- F1-score (cross-validation)
- Confusion matrices

## 📌 Key Results
- Best Logistic Regression parameter: C = 10
- Mean CV F1-score: ~0.485
- Logistic Regression performed comparably to Neural Network

- 
2. Run notebook:
- Open `.ipynb` file
- Run all cells in order

## 🔗 Repository Structure
- `emotion_classification_analysis.ipynb` → main notebook
- `README.md` → instructions

## 📌 Notes
- Ensure kernel is restarted and all cells are run sequentially
- Dataset must be loaded before modelling steps

## 🚀 How to Run

1. Install dependencies:
