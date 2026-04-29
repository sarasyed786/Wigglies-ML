# Wigglies Dataset using ML


## 📌 Project Overview
This project focuses on classifying ("wigglies") using deep learning models.

It was developed as part of a Kaggle competition:
THWS MAI – Introduction to Deep Learning (SS 2025)

The objective is to predict class labels from wigglies input data using machine learning models.

---

## ⚙️ Technologies Used
- Python
- PyTorch
- NumPy
- Matplotlib

---

## 🧠 Models Implemented

### 🔹 Multi-Layer Perceptron (MLP)
- Fully connected neural network
- Baseline model for classification

### 🔹 Convolutional Neural Network (CNN)
- Extracts temporal features from time-series
- Performs better than MLP on structured signals

---

## ⚙️ Workflow

1. Load dataset (`trainset.pth`, `testset_noLabels.pth`)
2. Preprocess time-series data
3. Train models (MLP & CNN)
4. Evaluate performance
5. Generate predictions for Kaggle submission

---

## 📊 Results

- CNN outperformed MLP in classification accuracy
---

## ▶️ How to Run

1. Open the notebook in Jupyter
2. Run all cells
3. Train models and generate predictions

---

## 📁 Project Structure

- `wigglies/` → dataset files  
- `scripts/` → model + training code notebooks  
- `outputs/` → results 

---

## 🏆 Kaggle Competition

Dataset and details available here:  
https://www.kaggle.com/competitions/thws-mai-idl-ss-25

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Data augmentation for time-series

---

## 👤 Author

Master’s Student in Artificial Intelligence  
THWS, Germany
