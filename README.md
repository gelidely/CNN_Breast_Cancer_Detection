# CNN_Breast_Cancer_Detection

PROJECT OVERVIEW:

Binary classification: cancer vs. no-cancer tissue in medical images via Convolutional Neural Networks (CNN)

Evolutionary algorithms to find optimal hyperparameters

Mount slides of breast cancer specimens at 40x magnification


IMAGE COUNTS:

Negative class: 198,738
Positive class: 78,786
Total: 277,524

Dataset size: 1.6 GB

Image size: 50 x 50 pixels


SUMMARY OF EVOLUTIONARY ALGORITHMS:

A systematic approach to find an optimal neural network model requires exploring a large combination of architectures and hyperparameters, which is very difficult to do manually (Miikkulainen et al., 2019).

Exploring 5 hyperparameter combinations (learning rate, number of epochs, steps per epoch, validation steps, and batch size) within known reasonable value bounds yields 100K possible models.

Adding model architecture exploration (number of layers, nodes per layer, regularization, pooling, activation functions, etc.) yields a combinatorial explosion of over 10 billion models.

Using 1,000 GPU’s and a conservative average time of 5 minutes to train each model would require almost a million hours, or about 100 years to explore the whole solution space using brute force with current technology!

Evolutionary algorithms use concepts from natural selection processes, especially neuroevolution, and applies them to the process of breeding the most fit models over the course of multiple generations until the best model is found for the task at hand (Stanley et al., 2019).
