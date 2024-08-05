# Deep Generative Models (DGM) - Summer of Code 2024

Welcome to the Deep Generative Models (DGM) project repository for the Summer of Code 2024, mentored by Aryan Bhosale. This repository contains the code and documentation for various assignments and projects related to deep generative models.

## Project Overview

The objective of this project is to explore and implement various deep generative models. Throughout the summer, we will work on different assignments and projects to understand and enhance the performance of these models. The focus will be on practical implementation, experimentation, and thorough documentation of the results.

## Assignments

### Assignment 1: Deep Convolutional Generative Adversarial Networks (DCGAN)

#### Summary

- **Objective**: Train a DCGAN, document the loss curves and minimum error, enhance the model to achieve better accuracy, and compare the generated images.
- **Files**:
  - `Assignment1_DCGAN.ipynb`: Jupyter Notebook containing the code for the assignment.
  - `Assignment1_DCGAN.pdf`: Documentation with results and observations.

### Assignment 2: Variational Autoencoders (VAEs)

#### Summary

- **Objective**: Implement and compare various VAE architectures:
  1. Basic vanilla VAE.
  2. VAE with encoder-decoder as encoder.
  3. VAE with encoder-decoder as decoder.
  4. VAE with encoder-decoder as both encoder and decoder.
- **Files**:
  - `Assign2.ipynb`: Jupyter Notebook containing the code for the assignment.
  - `assign2.pdf`: Documentation with results and observations.
### Assignment 3: Diffusion Models

#### Summary

- **Objective**: Implement a diffusion model and perform various experiments:
  1. Produce results with two sets of hyperparameters (varying learning rate, noising schedule (beta), and number of denoising steps). Attach loss curves for both trainings. Justify the choice of parameters and comment on observations.
  2. Produce one sample from each class (10 classes) in the CIFAR-10 dataset.
  3. Denoise a partially noised sample for 50, 10, and 5 iterations. Comment on the model's ability to denoise the sample and identify new features/shapes added during denoising.
- **Files**:
  - `Assignment3_KanishkSharma(22B1049).ipynb`: Jupyter Notebook containing the code for the assignment.
  - `assignment3-kanishksharma-22b1049.ipynb.pdf`: Documentation with results and observations.

### Documentation

All the documentation related to the assignments and projects, including detailed explanations, loss curves, error metrics, and sample images, will be maintained in the respective folders within this repository.

## Repository Structure

```
DGM/
│
├── Assignment1_DCGAN/
│   ├── Assignment1_DCGAN.ipynb  # Jupyter Notebook with code
│   └── Assignment1_DCGAN.pdf    # PDF with documentation
│
└── README.md                    # Project overview and assignment details

