# Gradients without Backpropagation
This repository contains an implementation of the paper [Gradients without backpropagation](https://arxiv.org/abs/2202.08587). 

## Description
For a better understanding of the mathematical concepts covered, we recommend first viewing the file `prerequisites.ipynb`. 

After understanding the mathematical concepts, we recommend proceeding with `fwdgrad.ipynb`: in this notwbook, the Forward Gradient Descent (FGD) algorithm is implemented on some known functions and on a convolutional network. For the convolutional network, the MNIST dataset have been used. In addition, there is also a comparison of model training using SDG and backpropagation.

## Installation
Implemented in [Python3](https://www.python.org/) using [Pytorch](https://pytorch.org/). 
Required packages: [Matplotlib](https://matplotlib.org/), [Numpy](https://numpy.org/), Pytorch(https://pytorch.org/). 

## References
All the references can also be find inside the python notebooks:
1. [Derivative](https://en.wikipedia.org/wiki/Derivative).
2. Kofi Asiedu Brempong, 2020 [I Finally Understood Backpropagation: And you can too...](https://towardsdatascience.com/i-finally-understood-backpropagation-and-you-can-too-44f7dd98ff52).
3. Atılım Gunes Baydin, Barak A. Pearlmutter, Don Syme, Frank Wood, Philip Torr, 2022. [Gradients without Backpropagation](https://arxiv.org/pdf/2202.08587.pdf).
4. [Dual number](https://en.wikipedia.org/wiki/Dual_number).
5. Mark Saroufim, 2019. [Automatic Differentiation Step by Step](https://marksaroufim.medium.com/automatic-differentiation-step-by-step-24240f97a6e6).
6. Robert Lange, 2019. [Forward Mode Automatic Differentiation & Dual Numbers](https://towardsdatascience.com/forward-mode-automatic-differentiation-dual-numbers-8f47351064bf).
7. Atılım Gunes Baydin, Barak A. Pearlmutter, Alexey Andreyevich Radul, Jeffrey Mark Siskind, 2018. [Automatic Differentiation in Machine Learning: a Survey](https://www.jmlr.org/papers/volume18/17-468/17-468.pdf).
8. Daniel Worrall, 2021. [Dual numbers](https://danielewworrall.github.io/blog/2021/08/dual-numbers/)
9. Robert Kübler, 2022. [Papers Simplified: Gradients without Backpropagation](https://towardsdatascience.com/papers-simplified-gradients-without-backpropagation-96e8533943fc).

## License
![Build Status](https://img.shields.io/github/license/luigi-ga/GradientsWithousBackpropagation)
This project is licensed under the MIT License

## Authors

- [@luigi-ga](https://github.com/luigi-ga)

Copyright (c) 2023 Luigi Gallo
