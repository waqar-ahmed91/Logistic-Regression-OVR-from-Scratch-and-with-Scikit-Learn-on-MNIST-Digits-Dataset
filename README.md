# Logistic Regression OVR from Scratch and with Scikit-Learn on MNIST Digits Dataset

This project demonstrates the implementation of **Logistic Regression** for multi-class classification using the **One-vs-Rest (OVR)** strategy. Two implementations are provided:

- A custom logistic regression model built from **scratch** using NumPy.
- A comparative implementation using **Scikit-Learn**'s `LogisticRegression`.

The MNIST Digits dataset (8x8 grayscale images of handwritten digits) is used as the benchmark for evaluating both implementations.

---

## 📌 Objectives

- Understand and implement logistic regression using gradient descent.
- Apply the **One-vs-Rest** approach for multi-class classification.
- Compare custom implementation results with Scikit-Learn’s optimized model.
- Evaluate performance using accuracy and classification reports.

---

## 🧠 Key Concepts

- **Logistic Regression:** A supervised learning algorithm used for binary classification, extended here to multi-class using OVR.
- **One-vs-Rest (OvR):** For multi-class problems, trains one binary classifier per class.
- **Gradient Descent:** Optimization technique used to minimize the loss function in the custom implementation.
- **MNIST Digits Dataset:** A simpler version of the original MNIST dataset (images of size 8x8 instead of 28x28), included in `sklearn.datasets`.

---

## 📁 Project Structure

```bash
logistic_regression_ovr/
├── custom_logistic_regression.py     # Implementation from scratch
├── sklearn_logistic_regression.py    # Scikit-learn implementation
├── utils.py                          # Helper functions (sigmoid, one-hot encoding, accuracy, etc.)
├── mnist_digits_demo.ipynb           # Jupyter notebook demonstration and evaluation
├── README.md                         # Project documentation
└── requirements.txt                  # Dependencies
```
## 📊 Evaluation Metrics

Accuracy Score
Classification Report
Confusion Matrix (optional)

## ✅ Results Summary

Implementation	Accuracy
From Scratch (OVR)	~X.XX%
Scikit-learn (OVR)	~X.XX%

Note: Results may vary slightly depending on learning rate, number of iterations, and regularization.

## 🛠️ Tools and Libraries

Python 3.x
NumPy
Scikit-learn
Matplotlib (optional for visualization)
Jupyter Notebook

## 📌 Future Improvements
Add regularization (L1/L2) in the scratch version.
Compare with other multi-class strategies like One-vs-One.

## 👤 Author
Waqar Ahmed
GitHub: @waqar-ahmed91

