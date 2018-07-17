# Digit Recognizer

| Model | Training Accuracy | Validation Accuracy | Test Accuracy | Epochs | Learning rate | Training time (in seconds) |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| [Neural Network](Neural%20Network.ipynb)  | 100%  | 97.7% | **97.64%** | 400 | 0.01 | 577.2 |
| [Neural Network with L2 regularization<br>and learning-rate decay](Neural%20Network%20with%20modifications.ipynb)   | 99.62%  | 98.18% | **98.1%** | 200 | <a href="https://www.codecogs.com/eqnedit.php?latex=\frac{1}{1&space;&plus;&space;0.001&space;*&space;epoch\_num}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{1}{1&space;&plus;&space;0.001&space;*&space;epoch\_num}" title="\frac{1}{1 + 0.001 * epoch\_num}" /></a> | 430.6 |
| [Convolutional Neural Network](Convolutional%20Neural%20Network.ipynb)  | 99.75%  | 98.88% | **99.07%** | 80 | 0.01 | 312.8 |

These models have been trained using Nvidia Tesla K80 GPU on the Google Colab platform.
