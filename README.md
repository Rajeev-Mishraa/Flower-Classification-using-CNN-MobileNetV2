# Flower-Classification-using-CNN-MobileNetV2
🌸 Flower Classification using CNN &amp; MobileNetV2

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![DeepLearning](https://img.shields.io/badge/Deep%20Learning-CNN-brightgreen)
![Status](https://img.shields.io/badge/Project-Completed-success)

A deep learning project that classifies **5 flower species**  
(*daisy, dandelion, rose, sunflower, tulip*) using:

- A **Custom CNN Model**
- **Transfer Learning with MobileNetV2**

---

## 🚀 Features
- Load images using `image_dataset_from_directory`
- Normalization + Data Augmentation pipeline
- Custom CNN architecture
- Transfer Learning with MobileNetV2
- Confusion Matrix + Classification Report

---

## 📂 Dataset
Kaggle — **Flowers Recognition Dataset**

Contains 5 classes:
- daisy  
- dandelion  
- rose  
- sunflower  
- tulip  

---

## 🧠 Models Used

### 1️⃣ Custom CNN
- 3× Conv2D + MaxPooling layers  
- Dropout layers  
- Dense classification head  

### 2️⃣ MobileNetV2 Transfer Learning
- Pretrained on ImageNet  
- Frozen base model  
- Custom dense head  
- Dropout regularization  

---

## 📊 Evaluation
- Accuracy & Loss curves  
- Confusion Matrix  
- Classification Report  
- Visualization of predictions  

---

## 📈 Results

| Model | Accuracy | Notes |
|-------|----------|-------|
| Custom CNN | Moderate | Overfitting present |
| MobileNetV2 | ⭐ High | Better generalization & faster training |

---

## 📌 Future Improvements
- Fine-tune deeper MobileNetV2 layers  
- Additional data augmentation  
- Class weighting  
- Try EfficientNet or ResNet models  

---

## 🏁 Conclusion
Transfer Learning with **MobileNetV2** provides a strong, efficient model for flower image classification—significantly outperforming a simple CNN.  
This project demonstrates practical CNN skills & modern deep-learning workflows.
