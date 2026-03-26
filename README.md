# final-project-caralyon
Human Activity Recognition (HAR) project using the UCI HAR dataset, where multiple approaches including Machine Learning ,Deep Learning (CNN, CNN+LSTM), Hybrid models (CNN+SVM), and Self-Supervised Learning were implemented and compared. The project achieves up to ~95% accuracy self-supervised learning reduces dependence on labeled data.
# 🚀 Human Activity Recognition (HAR)

## 📌 Overview
This project focuses on **Human Activity Recognition (HAR)** using smartphone sensor data from the UCI HAR dataset. The goal is to classify human activities such as walking, sitting, and standing using multiple machine learning and deep learning approaches.

---

## 🎯 Objectives
- Compare Machine Learning vs Deep Learning models
- Build hybrid models to improve accuracy
- Explore Self-Supervised Learning (SSL)
- Analyze model performance using visualizations

---

## 📊 Dataset
- **Dataset**: UCI Human Activity Recognition
- **Samples**: 10,299
- **Features**: 561
- **Activities**:
  - Walking
  - Walking Upstairs
  - Walking Downstairs
  - Sitting
  - Standing
  - Laying
- **Sensors**:
  - Accelerometer
  - Gyroscope

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 🧠 Models Implemented

### 🔹 Machine Learning
- Random Forest
- Support Vector Machine (SVM)

### 🔹 Deep Learning
- Convolutional Neural Network (CNN)
- CNN + LSTM

### 🔹 Hybrid Model
- CNN (feature extraction) + SVM (classification)

### 🔹 Self-Supervised Learning (SSL)
- Denoising Autoencoder
- Transformation-based SSL
- Transfer Learning

---

## 📈 Results

| Model              | Accuracy |
|-------------------|----------|
| SVM               | ~96%     |
| Hybrid (CNN+SVM)  | ~94–95%  |
| CNN               | ~93%     |
| CNN + LSTM        | ~93%     |
| SSL (Improved)    | ~92–93%  |
| Random Forest     | ~92%     |
| Autoencoder       | ~86–87%  |

---

## 📊 Visualizations
- Activity distribution
- PCA visualization
- Confusion matrices
- Training vs validation accuracy
- Model comparison graphs

---

## 🔍 Key Insights
- Hybrid models outperform standalone models
- CNN effectively captures motion patterns
- SVM performs well on high-dimensional data
- Self-supervised learning reduces dependency on labeled data

---

## 🏁 Conclusion
This project demonstrates that combining machine learning and deep learning techniques significantly improves performance in human activity recognition tasks.

---

## 🔮 Future Work
- Implement transformer-based models
- Deploy real-time HAR system
- Optimize models for mobile devices

