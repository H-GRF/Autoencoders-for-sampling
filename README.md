# Variational Autoencoder (VAE) for MNIST Image Generation in R

This repository demonstrates the implementation of a **Variational Autoencoder (VAE)** in R, specifically for generating handwritten digit images from the MNIST dataset. The project highlights the generative capabilities of VAEs, enabling the synthesis of new images based on the learned latent representations.

## Project Overview

The primary objective of this project is to explore the power of Variational Autoencoders in generating realistic images of handwritten digits. Unlike standard Autoencoders, VAEs impose a probabilistic structure on the latent space, making them ideal for image generation tasks.

## Key Features

- **Dataset**: Preprocessing the MNIST dataset, including normalization and reshaping.
- **Model**: Construction and training of a Variational Autoencoder using the **Keras** library in R.
- **Output**: Generation of new handwritten digit images by sampling from the learned latent space.
- **Visualization**: Displaying both reconstructed images and newly generated samples.

## Prerequisites

To run this project, ensure the following are installed:

- **R** (version ≥ 4.0.0 recommended)
- **TensorFlow** and **Keras** configured for R
- Required R packages: `reticulate`, `keras`, `tidyverse`, `tidymodels`, `ggplot2`, `reshape2`

### Important Note

You must install and configure **Keras** and **TensorFlow** for R. Use the `install_keras()` function to set up the environment correctly.


## Remarks

- The project utilizes **Variational Autoencoders (VAEs)** to generate new samples, making it distinct from standard Autoencoders.
- Ensure TensorFlow and Keras are properly installed and configured before running the code.
- The generated images provide insights into how VAEs model and generate data distributions.

## Author

This project was created by [Hamza Gouaref](mailto:gouarefhamza@gmail.com). For questions or feedback, feel free to reach out.

