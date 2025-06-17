# 🧠 Handwritten Digit Recognition using CNN and OpenCV

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) using a real image dataset. The images are resized and normalized using OpenCV, and the model is trained
and evaluated using TensorFlow/Keras.

---

## 📂 Dataset
- Source: `sklearn.datasets.load_digits`
- Images: 8×8 grayscale digits, resized to 28×28 for CNN input
- No Kaggle API required

---

## 🧠 Model Architecture
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten → Dense (128) → Dense (10)
- Loss: Categorical Crossentropy
- Optimizer: Adam

---

## 🔎 Accuracy
- ✅ Achieved over **98% accuracy** on test data

---

## 💡 Sample Prediction

```python
predict_custom(5)
# Displays predicted and actual digit with image
