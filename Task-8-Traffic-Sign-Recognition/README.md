# 🚦 Task 8 – Traffic Sign Recognition

## 📌 Overview
Build a deep learning model to classify traffic signs from images.  
This is a **multi-class image classification problem**, widely applied in autonomous driving systems.

## 🗂 Dataset
- Recommended: [GTSRB (German Traffic Sign Recognition Benchmark)](eowmeowmeowmeowmeow/gtsrb-german-traffic-sign)  
- Images of traffic signs belonging to multiple categories.  
- Target: Traffic sign class (multi-class label)

## ⚙️ Approach
- Preprocessed images (resize, normalize, augment)  
- Built a **Convolutional Neural Network (CNN)** using TensorFlow/Keras  
- Trained the CNN on multiple traffic sign classes  
- Evaluated with accuracy, precision, recall, F1-score, and confusion matrix  
- Bonus: Compared **custom CNN** with transfer learning (e.g., MobileNet)
- Trained both models for 30 epochs  

## 📈 Results
### 🔹 Custom CNN
- **Final Test Accuracy:** 99.63%  
- Training and validation curves show smooth convergence with minimal overfitting.  
- Outstanding generalization on unseen test data.

### 🔹 MobileNet (Transfer Learning)
- **Final Test Accuracy:** 39.7%  
- Training/validation loss remained high, suggesting poor transfer for this dataset.  
- Significantly underperformed compared to the custom CNN.

📊 **Key Insights:**  
- The **Custom CNN** clearly outperformed MobileNet, achieving near-perfect accuracy.  
- Data preprocessing (resizing, normalization, augmentation) was critical to model success.  
- Some signs with visual similarities were more challenging, but overall misclassification was minimal.  

## 🛠 Tools
Python, TensorFlow, Keras, OpenCV, Matplotlib
