# ANN (Feedforward Neural Networks) using PyTorch

This repository contains two Artificial Neural Network (ANN) projects implemented using **PyTorch**, focusing on both regression and classification tasks.

## Projects Included

### 1. ANN Regressor (Power Plant Dataset)

* Predicts energy output of a power plant
* Type: Regression
* Model: Feedforward Neural Network (FNN)

**Results:**

* Training MSE :  355.9460754394531
* Testing MSE :  348.7286376953125
* r^2 score :  -0.21871680858994158


### 2. ANN Classifier (Date Fruit Dataset)

* Classifies different types of date fruits
* Type: Classification
* Model: Feedforward Neural Network (FNN)

**Results:**

* accuracy:  93.88888888888889

## ⚙️ Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* PyTorch

---

## 🧠 Model Implementation (PyTorch)

* Built neural networks using PyTorch
* Implemented custom feedforward neural networks (FNNs)
* Used tensors, forward propagation, and backpropagation
* Defined loss functions and optimizers manually

---

## ⚙️ Training Details

* **Loss Functions:**

  * Regression → MSELoss
  * Classification → CrossEntropyLoss

* **Optimizer:**

  * Adam

* **Framework:**

  * PyTorch

---

## 🔍 Key Concepts Used

* Data preprocessing
* Handling missing values
* Feature scaling
* Label encoding
* Train-test split
* Neural network architecture design
* Model evaluation

---

## How to Run

```bash
git clone https://github.com/ciphermosaic/ANNs.git
cd ANNs
pip install -r requirements.txt
```

Run the scripts:

```bash
python ANN_Regression.ipynb
python ANN_Classification.ipynb

```

## 📊 Notes

* Projects were developed using Google Colab
* Update dataset paths before running locally

## 👤 Author

Abubakar

## Licence

MIT
