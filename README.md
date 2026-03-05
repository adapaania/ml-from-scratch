# ML From Scratch

A personal repository documenting my journey of learning machine learning by **implementing algorithms from scratch using NumPy**.

Instead of relying on high-level libraries such as `scikit-learn`, the goal of this project is to understand **how machine learning algorithms work internally** by building them step-by-step.

Each implementation focuses on:

* mathematical intuition
* algorithm implementation
* optimization methods
* model evaluation
* experiments and insights

---

# Learning Progress

| Algorithm                    | Status         | Notes                        |
| ---------------------------- | -------------- | ---------------------------- |
| Linear Regression            | ✅ Implemented  | SGD + Batch Gradient Descent |
| Polynomial Regression        | 🔄 In Progress | Feature mapping              |
| Cross Validation             | 🔄 In Progress | k-fold cross validation      |
| Logistic Regression          | ⏳ Planned      | Binary classification        |
| Linear Discriminant Analysis | ⏳ Planned      | Gaussian generative model    |
| Support Vector Machines      | ⏳ Planned      | Hard margin + soft margin    |
| Decision Trees               | ⏳ Planned      | CART algorithm               |
| Random Forest                | ⏳ Planned      | Bagging ensemble             |
| PCA                          | ⏳ Planned      | Dimensionality reduction     |
| Neural Networks              | ⏳ Planned      | Backpropagation              |

---

# Motivation

Machine learning libraries make it easy to train models, but they hide the underlying mechanics.

This repository focuses on learning **machine learning fundamentals** by implementing algorithms manually using **linear algebra and optimization techniques**.

The main goals are to understand:

* how models learn from data
* how gradient-based optimization works
* how model performance is evaluated
* how statistical assumptions influence predictions

---

# Implemented Algorithms

## Linear Regression

Implemented linear regression using gradient-based optimization.

Concepts covered:

* Mean Squared Error (MSE)
* Gradient Descent
* Stochastic Gradient Descent (SGD)
* Batch Gradient Descent
* Bias term
* Prediction function
* Loss minimization

Evaluation metrics implemented:

* RMSE
* R² score

Experiments:

* learning rate comparison
* convergence visualization
* gradient descent behavior

---

## Polynomial Regression (Work in Progress)

Extends linear regression using polynomial feature transformations.

Concepts covered:

* feature mapping
* model complexity
* underfitting vs overfitting
* polynomial degree selection

---

## Cross Validation (Work in Progress)

Implementation of **k-fold cross validation** for model selection.

Concepts covered:

* model evaluation
* hyperparameter tuning
* validation sets
* generalization error

---

## Planned Implementations

Future algorithms planned for this repository:

* Logistic Regression
* Linear Discriminant Analysis
* Support Vector Machines
* Decision Trees
* Random Forests
* Principal Component Analysis (PCA)
* Neural Networks from scratch

Each algorithm will include:

* mathematical explanation
* implementation
* experiments and insights

---

# Repository Structure

```
ml-from-scratch/

notebooks/
│
├── 01_linear_regression.ipynb
├── 02_polynomial_regression.ipynb
├── 03_cross_validation.ipynb
├── 04_lda.ipynb
└── 05_svm.ipynb

src/
│
├── linear_regression.py
├── polynomial_features.py
├── cross_validation.py
├── lda.py
└── svm.py
```

---

# Technologies Used

* Python
* NumPy
* Matplotlib
* Jupyter Notebook

No machine learning frameworks are used for training models.

---

# Learning Philosophy

This repository focuses on understanding machine learning by implementing algorithms from **first principles**.

Each model is implemented following this approach:

1. Understand the mathematical formulation
2. Implement the algorithm using NumPy
3. Train the model using optimization techniques
4. Evaluate the model using appropriate metrics
5. Analyze results and model behavior

The goal is to develop **deep intuition for machine learning algorithms**, not just their usage.

---

# How to Run

Clone the repository:

```
git clone https://github.com/adapaania/ml-from-scratch.git
cd ml-from-scratch
```

Install dependencies:

```
pip install numpy matplotlib jupyter
```

Run Jupyter Notebook:

```
jupyter notebook
```

---

# Author

Aania Adap
Master's Student in Computer Science

GitHub: [https://github.com/adapaania](https://github.com/adapaania)

---
