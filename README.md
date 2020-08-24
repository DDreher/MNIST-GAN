# Hello GAN - Vanilla GAN / Wasserstein GAN trained on MNIST
Basic implementation of a vanilla GAN /  Wasserstein GAN trained on the MNIST dataset. This code was only written for educational purposes.

## Overview

In this Jupyter Notebook GANs are implemented according to [NIPS 2016 Tutorial: Generative Adversarial Networks](https://arxiv.org/pdf/1701.00160.pdf) and trained on the MNIST dataset.
To tackle the unstable training of GANs the following methods were proposed:
* Balancing discriminator and generator losses to ensure sufficient gradients for generator training
* Introducing label noise to prevent the discriminator from training too quickly

Additionally the usage of the Wasserstein distance was explored as described in [Wasserstein GAN by Arjovsky et al., 2017](https://arxiv.org/pdf/1701.07875.pdf)  

## Results

### MNIST samples
<img src="https://github.com/DDreher/MNIST-GAN/blob/master/images/mnist_samples.png"/>

### GAN output samples
<img src="https://github.com/DDreher/MNIST-GAN/blob/master/images/generated_images.png"/>

## Dependencies

* Python 3.6
* TensorFlow 1.15
* Numpy
* Matplotlib
