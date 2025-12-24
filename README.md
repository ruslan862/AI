# Task X: Plant Disease Classification (PlantVillage)

**Student:** Ruslan Asgarov  
**ID:** 13  
**Seed:** 20240113

---

## 📊 Project Overview

This project focuses on **plant disease classification** using the **PlantVillage dataset**.  
A Convolutional Neural Network (CNN)–based model was trained to classify **three conditions of a single plant type**.

- **Dataset:** PlantVillage  
- **Plant selected:** Tomato  
- **Number of classes:** 3  
- **Target accuracy:** ≥ 88%

### Tomato Classes
- Healthy  
- Early Blight  
- Late Blight  

---

## 🎤 Presentation

[View Presentation Slides](https://drive.google.com/your-link-here)

---

## 📁 Dataset Details

- **Name:** PlantVillage (Tomato subset)
- **Classes:** 3
- **Training samples:** XXXX
- **Validation samples:** XXXX
- **Test samples:** XXXX

Dataset was split into training, validation, and test sets using a fixed random seed for reproducibility.

---

## 🧠 Model Architecture

- **Type:** CNN  
- **Input size:** 224 × 224 × 3  
- **Convolutional layers:** X  
- **Fully connected layers:** X  
- **Activation function:** ReLU  
- **Output layer:** Softmax (3 classes)  
- **Total parameters:** XXXXXXX  

---

## ⚙️ Training Comparison

Two different training configurations were tested and compared.

### 🔹 Version 1
- **Learning rate:** 0.001  
- **Batch size:** 32  
- **Optimizer:** Adam  
- **Epochs:** XX  
- **Test accuracy:** XX.XX%

---

### 🔹 Version 2
- **Learning rate:** 0.0001  
- **Batch size:** 32  
- **Optimizer:** Adam  
- **Epochs:** XX  
- **Test accuracy:** XX.XX%

---

## 🏆 Best Result

- **Best version:** Version X  
- **Final test accuracy:** XX.XX%  
- **Target accuracy:** 88%  
- **Status:** ✓ Achieved  

---

## 📈 Analysis

- **Best performing class:** Tomato Healthy  
- **Worst performing class:** Tomato Late Blight  
- **Key observations:**
  - Lower learning rate improved generalization.
  - Data augmentation helped reduce overfitting.
  - Class imbalance slightly affected Late Blight accuracy.
