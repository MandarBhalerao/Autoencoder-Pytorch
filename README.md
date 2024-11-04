# Autoencoder Implementation in PyTorch

## Overview
This repository demonstrates the training of autoencoders using the MNIST dataset of handwritten digits. The project explores two types of neural network architectures: an Artificial Neural Network (ANN) and a Convolutional Neural Network (CNN), implemented from scratch using PyTorch.

## Autoencoder Theory
Autoencoders are unsupervised learning models that aim to learn a compressed representation of data. They are typically used for dimensionality reduction or feature extraction. The fundamental components of an autoencoder are:
- **Encoder**: Compresses the input into a smaller, encoded representation in a latent space.
- **Decoder**: Attempts to reconstruct the input data from the encoded representation, effectively learning the data's important features while ignoring insignificant details (noise).

## Dataset
The MNIST dataset, which comprises images of handwritten digits, serves as the training data. It is ideal for evaluating the effectiveness of the encoding and decoding capabilities of autoencoders due to its simplicity and standardization in image processing and machine learning communities.

## Implementation
The implementation involves two different architectural approaches:
- **ANN-based Autoencoder**: Uses fully connected layers to handle the encoding and decoding processes.
- **CNN-based Autoencoder**: Leverages convolutional layers, which are more suited for image data due to their ability to capture spatial hierarchies in images.

## Training
Both models were trained to minimize the reconstruction loss, quantifying the difference between the original images and the reconstructed outputs from the autoencoders.

## Observations
Comparative analysis of the output images revealed:
- The CNN-based autoencoder generally produced better results, with clearer and more precise reconstructions.
- The ANN-based model, while effective, did not achieve the same level of clarity and detail as the CNN model.

## Conclusion
The superior performance of the CNN-based autoencoder underscores its suitability for image-related tasks, offering insights into more efficient architectural choices for similar applications.
