### Autoencoder - encode 4 variables into 3
![Autoencoder](/imgs/Autoencoder.jpeg)

The presentation for this project can be found [here](https://docs.google.com/presentation/d/1fmdpi0x3zCWyJqMD0G5bOToJ3lpEUaBfRiVmZHHr7X8/edit?usp=sharing).

Below are few of the models I tried and the corresponding `MSE Losses` for those models.

Architecture | MSE loss|
-------------|----------
CNN          | ~0.053  |
NN with only Linear and Tanh layers | ~0.021 |
NN with BatchNorm layers | 0.0161 |
NN with BatchNorm layers and with singular values added in the data | 0.0073 |
