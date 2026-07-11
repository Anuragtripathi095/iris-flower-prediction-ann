# Iris Flower Classification using Artificial Neural Network (ANN)

## 📌 Project Overview

This project implements an Artificial Neural Network (ANN) using TensorFlow and Keras to classify Iris flowers into three different species based on their flower measurements.

The model is trained on the famous Iris dataset and predicts the species using four input features.

---

## 📂 Dataset

The Iris dataset contains 150 flower samples with four input features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Classes:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

---

## 🧠 ANN Model Architecture

Input Layer:
- 4 Input Features

Hidden Layer 1:
- 16 Neurons
- ReLU Activation

Hidden Layer 2:
- 8 Neurons
- ReLU Activation

Output Layer:
- 3 Neurons
- Softmax Activation

---

## ⚙ Model Training

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 100
- Batch Size: 8
- Validation Split: 20%

---

## 📊 Workflow

1. Load Iris Dataset
2. Preprocess Data
3. Split into Training and Testing Sets
4. Scale Features
5. One-Hot Encode Labels
6. Build ANN Model
7. Train the Model
8. Evaluate Performance
9. Save the Trained Model
10. Predict New Flower Species

---

## 📁 Project Structure

```
iris-flower-classification-ann/
│
├── Iris_prediction.ipynb
├── iris_model.h5
├── scaler.pkl
├── requirements.txt
├── README.md
└── images/
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/your-username/iris-flower-classification-ann.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook Iris_prediction.ipynb
```

---

## 📈 Model Output

The trained model predicts one of the following classes:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

---

## 💾 Model Saving

```python
model.save("iris_model.h5")
```

Load the saved model

```python
from tensorflow.keras.models import load_model

model = load_model("iris_model.h5")
```

---

## 👨‍💻 Author

Anurag Tripathi
