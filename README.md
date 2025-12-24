# Task 1: Plant Disease Classification – Tomato Leaf

**Student:** Ruslan Asgarov  
**ID:** 13  
**Seed:** 20240113  

## Presentation
[View Presentation Slides](./Plant_Disease_3slides.pptx)

## Dataset
- **Name:** PlantVillage (Tomato subset)  
- **Classes:** 3 (Healthy, Early Blight, Late Blight)  
- **Training samples:** 3000 (example)  
- **Test samples:** 600 (example)  

## Model Architecture
- **Type:** ResNet18 (pre-trained)  
- **Convolutional layers:** 17  
- **Fully connected layers:** 1 (fc layer 512→3)  
- **Total parameters:** ~11.7M  

## Training Comparison

### Version 1
- **Learning rate:** 0.0001  
- **Batch size:** 32  
- **Optimizer:** Adam  
- **Test accuracy:** 87%  

### Version 2
- **Learning rate:** 0.00001  
- **Batch size:** 32  
- **Optimizer:** Adam  
- **Test accuracy:** 85%  

### Best Result
- **Best version:** Version 1  
- **Final test accuracy:** 87%  
- **Target accuracy:** 88%  
- **Status:** ✗ Below target  

## Analysis
- **Best performing class:** Healthy  
- **Worst performing class:** Early Blight  
- **Key observations:**  
  The model performs very well on healthy leaves. Some confusion occurs between Early Blight and Late Blight classes. Reducing learning rate in Version 2 slightly decreased accuracy.

## Files
- `Plant_Disease_3slides.pptx`: 3-slide presentation with overview, training comparison, and best results  
- `notebook.ipynb`: (if available) Implementation of model and evaluation  
- `results/training_comparison.png`: Training curves for both versions (optional)  
- `results/confusion_matrix.png`: Confusion matrix for best model (optional)  
- `results/predictions.png`: Sample predictions from test set (optional)
