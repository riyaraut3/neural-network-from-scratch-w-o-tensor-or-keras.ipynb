# Neural Network from Scratch (without TensorFlow or Keras)

## Project Overview

This project implements a simple neural network from scratch using only basic Python libraries like `numpy`. The network is trained on the MNIST dataset, a collection of 70,000 images of handwritten digits (0-9). The goal is to classify these digits accurately.

## Dataset

- **Dataset**: MNIST Handwritten Digits
- **Source**: The dataset is fetched using the `fetch_openml` function from `sklearn.datasets`.
- **Features**: 784 (28x28 pixel values normalized to range [0, 1])
- **Labels**: Digits (0-9), represented in one-hot encoded format.

## Project Structure

- **`neural_network_from_scratch_w_o_tensor_or_keras.ipynb`**: The Jupyter notebook containing the entire code for building, training, and evaluating the neural network.

## Dependencies

To run this notebook, you need the following Python libraries:

- `numpy`
- `matplotlib`
- `sklearn`

You can install the dependencies using the following command:

```bash
pip install numpy matplotlib scikit-learn
