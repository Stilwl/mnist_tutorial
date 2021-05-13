# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2

# For students from SJTU
Please read [HEAR](EE369.md).

# Result

|      | Train accuracy | Test accuracy |
| :--: | :------------: | :-----------: |
|  Q1  |     97.38%     |    87.30%     |
|  Q2  |     82.02%     |    80.50%     |
|  Q3  |     97.65%     |    86.10%     |
|  Q4  |     95.90%     |    87.30%     |

|   Q5   | Train accuracy | Test accuracy |
| :----: | :------------: | :-----------: |
| Epoch0 |    90.363%     |    97.596%    |
| Epoch1 |    97.404%     |    98.377%    |
| Epoch2 |    98.137%     |    98.608%    |
| Epoch3 |    98.589%     |    98.738%    |
| Epoch4 |    98.821%     |    98.928%    |
| Epoch5 |    99.017%     |    98.878%    |
| Epoch6 |    99.229%     |    98.838%    |
| Epoch7 |    99.289%     |    99.099%    |
| Epoch8 |    99.332%     |    99.028%    |
| Epoch9 |    99.447%     |    98.668%    |

* Pytorch

LeNet-5 for training.

