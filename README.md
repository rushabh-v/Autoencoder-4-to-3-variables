### Autoencoder - encode 4 variables into 3
![Autoencoder](/imgs/Autoencoder.jpeg)


Below are few of the models I tried and the corresponding `MSE Losses` for those models.

Architecture | MSE loss|
-------------|----------
NN with only Linear and Tanh layers | ~0.021 |
NN with Linear, Tanh and BatchNorm layers | 0.0161 |
NN with Linear, Tanh and BatchNorm layers, and with principal components concatenated to the Data | 0.00774 |
NN with Linear, Tanh and BatchNorm layers, and with singular values concatenated to the Data | 0.00706 |

