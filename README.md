# 🧠 MIST Handwritten Digits Recognition Using ANN

A deep learning project that classifies handwritten digits (0–9) using an **Artificial Neural Network (ANN)** trained on the **MNIST dataset**. The model learns meaningful patterns from grayscale images and accurately predicts the corresponding digit class.

---

## 📌 Project Overview

Handwritten digit recognition is one of the most fundamental problems in computer vision and pattern recognition. In this project, an Artificial Neural Network is developed using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

The project demonstrates the complete deep learning workflow, including data preprocessing, model development, training, evaluation, and prediction.

---

## 🎯 Objectives

- Build an Artificial Neural Network for image classification.
- Classify handwritten digits from **0 to 9**.
- Preprocess image data for neural network training.
- Evaluate model performance using standard classification metrics.
- Visualize predictions on unseen handwritten digits.

---

## 📂 Dataset

**Dataset:** MNIST Handwritten Digits Dataset

- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28 pixels
- **Color Format:** Grayscale
- **Number of Classes:** 10 (Digits 0–9)

The dataset is available directly through TensorFlow/Keras.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| TensorFlow | Deep Learning Framework |
| Keras | Neural Network API |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Google Colab / Jupyter Notebook | Development Environment |

---

## 🧠 ANN Architecture

The neural network consists of:

- Input Layer
- Flatten Layer
- Dense Hidden Layer (ReLU Activation)
- Dense Hidden Layer (ReLU Activation)
- Output Layer (Softmax Activation)

---

## 🔄 Project Workflow

```
Load Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Normalize Pixel Values
      │
      ▼
Build ANN Model
      │
      ▼
Train Model
      │
      ▼
Evaluate Accuracy
      │
      ▼
Predict Handwritten Digits
```

---

## 📊 Model Performance

The model is evaluated using:

- Training Accuracy
- Testing Accuracy
- Loss
- Accuracy Curves
- Prediction Visualization

> **Note:** Update this section with your actual results after training.

Example:

| Metric | Value |
|---------|-------|
| Training Accuracy | 98.9% |
| Testing Accuracy | 97.8% |
| Test Loss | 0.08 |

---

## 📁 Project Structure

```
Image-Classification-of-Handwritten-Digits-Using-ANN/
│
├── data/
├── images/
├── notebooks/
│   └── MNIST_ANN.ipynb
├── models/
├── requirements.txt
├── README.md
└── LICENSE
```
---

## 📸 Sample Output

Include screenshots such as:

- Sample MNIST images
- Training & Validation Accuracy Curve
- Loss Curve
- Prediction Results
- Confusion Matrix (Optional)

Example:

```
Predicted Digit : 7
Actual Digit    : 7
Confidence      : 99.8%
```

---

## 💡 Key Learning Outcomes

- Artificial Neural Networks (ANN)
- Image Classification
- Data Preprocessing
- TensorFlow & Keras
- Multi-class Classification
- Deep Learning Fundamentals
- Model Evaluation
- Computer Vision Basics

---

## 🔮 Future Improvements

- Implement Convolutional Neural Networks (CNN) for higher accuracy.
- Add Hyperparameter Tuning.
- Deploy the model using Streamlit or Flask.
- Build a real-time handwritten digit recognition web application.
- Compare ANN with CNN performance.

---

## 🤝 Contributing

Contributions are welcome.

If you would like to improve this project, feel free to fork the repository and submit a pull request.

---

## ⭐ If you found this project useful

Give this repository a ⭐ to support the project and help others discover it.

---

## 📬 Contact

**Lokesh**

GitHub: https://github.com/kopparthiLokesh

LinkedIn: https://www.linkedin.com/in/kopparthilokesh/

---

## 📄 License

This project is licensed under the MIT License.
