# 🐾 Animal Classification Using CNN

### 🧠 Assignment  — Multi-Class Classification

This project uses a **Convolutional Neural Network (CNN)** to classify animal images into **5 different species**.

## 🎯 Objective

Build a CNN model that can learn visual features from animal images and predict the correct animal class.

## 📦 Dataset

**Kaggle:** Animal Image Classification – 5 Species
**Dataset ID:** `miadul/animal-image-classification-5-species`

## 🧠 Model

```text
Input Image
    ↓
Conv2D → MaxPooling
    ↓
Conv2D → MaxPooling
    ↓
Conv2D → MaxPooling
    ↓
Flatten → Dense → Dropout
    ↓
Softmax Prediction 🐾
```

## 🛠️ Tools

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## 📊 Evaluation

The model is evaluated using:

* Accuracy
* Loss graphs
* Confusion Matrix
* Classification Report
* Sample Predictions

## 🚀 How to Run

Open the notebook in **Google Colab**, run the cells from top to bottom, and the dataset will be downloaded automatically.

## 💡 Learning Outcome

Through this project, I learned how to:

* Prepare image data
* Build a CNN
* Train a Deep Learning model
* Evaluate classification results
* Make predictions on unseen images

## 🏁 Conclusion

This project demonstrates how CNNs can learn patterns from images and use them to **recognize different animal species**.

🐾 **Images → CNN → Prediction**
