# Deep Learning Codes

Hands-on notebooks covering the foundations of deep learning, from a single perceptron to neural networks built with Keras.

## Contents

| Notebook | What it covers |
|---|---|
| [Basic Perceptron.ipynb](Basic%20Perceptron.ipynb) | Perceptron classifier using scikit-learn, with decision-boundary visualisation |
| [perceptron-trick.ipynb](perceptron-trick.ipynb) | The perceptron trick: updating weights step by step on a synthetic classification dataset |
| [keras-library-deep-learning.ipynb](keras-library-deep-learning.ipynb) | A first neural network with Keras `Sequential` and `Dense` layers, with feature scaling and accuracy evaluation |
| [mnist_DL.ipynb](mnist_DL.ipynb) | Handwritten digit classification on MNIST using a Keras `Flatten` + `Dense` network |
| [gradient_descent.ipynb](gradient_descent.ipynb) | Gradient descent for linear regression, comparing a manual implementation against scikit-learn's `LinearRegression` |

**Data:** [placement.csv](placement.csv) is a small dataset (`cgpa`, `resume_score`, `placed`) used to predict student placement.

## Tech stack

Python, NumPy, pandas, Matplotlib, Seaborn, scikit-learn, TensorFlow / Keras

## Getting started

```bash
git clone https://github.com/setia08/Deep-Learning-Codes.git
cd Deep-Learning-Codes
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
jupyter notebook
```

## Learning path

1. Basic Perceptron
2. Perceptron trick
3. Neural networks with Keras
4. MNIST digit classification
5. Gradient descent
