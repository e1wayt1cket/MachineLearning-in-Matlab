# Machine Learning in MATLAB

Implementation of machine learning algorithms in MATLAB, based on coursework from Stanford's Machine Learning course (CS229 / Andrew Ng's ML course).

## Contents

### Multi-class Classification and Neural Networks (ex3)

Implementation of multi-class logistic regression and feedforward neural networks for handwritten digit recognition.

**Key files:**

| File | Description |
|------|-------------|
| `ex3.m` | Main script: multi-class classification |
| `ex3_nn.m` | Main script: neural network prediction |
| `lrCostFunction.m` | Regularized logistic regression cost function |
| `oneVsAll.m` | One-vs-all multi-class classifier training |
| `predictOneVsAll.m` | Prediction using trained one-vs-all classifiers |
| `predict.m` | Neural network prediction function |
| `sigmoid.m` | Sigmoid activation function |
| `displayData.m` | Display a grid of handwritten digits |
| `fmincg.m` | Conjugate gradient optimization |

### Data

- `ex3data1.mat` — 5000 training examples of handwritten digits (20x20 pixels each)
- `ex3weights.mat` — Pre-trained neural network weights for digit recognition

## Usage

Open MATLAB and run:

```matlab
% Multi-class logistic regression
ex3

% Neural network prediction
ex3_nn
```

## Setup

Requires MATLAB (R2019b or later recommended). No additional toolboxes are required beyond the standard MATLAB environment.
