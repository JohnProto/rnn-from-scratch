# RNN From Scratch

This project implements a Recurrent Neural Network (RNN) from scratch in Python using NumPy. It includes the implementation of a character-level language model to generate new text based on a given dataset.

## Project Structure

- `Assignment5_4999.pdf`: This document explains the theoretical concepts behind RNNs and provides instructions for the implementation.
- `assign_5a.ipynb`: A Jupyter notebook that implements the forward pass of a simple RNN and a GRU cell.
- `assign_5b.ipynb`: A Jupyter notebook that implements a character-level language model using the RNN from the first part. This includes the backward pass, gradient clipping, and a training loop.
- `data/`: This directory is not present, but it is expected to contain the datasets used for training the language model. The notebook `assign_5b.ipynb` refers to `element_list.txt` and `movie_title_list.txt`.

## Getting Started

To run the code in this project, you will need to have Python 3 and Jupyter Notebook installed. You will also need to install the following Python libraries:

- `numpy`

You can install the required libraries using pip:

```bash
pip install numpy
```

Once you have the required libraries installed, you can run the Jupyter notebooks:

```bash
jupyter notebook assign_5a.ipynb
jupyter notebook assign_5b.ipynb
```

**Note:** The `assign_5b.ipynb` notebook expects the training data to be in a `data` directory. You will need to create this directory and place the `element_list.txt` and `movie_title_list.txt` files in it.

## Datasets

The character-level language model is trained on two datasets:

- `element_list.txt`: A list of names of existing chemical elements.
- `movie_title_list.txt`: A list of different movie titles.

The model learns the patterns in the text and can be used to generate new, similar text.

## Theoretical Concepts

This project covers the following theoretical concepts:

- Recurrent Neural Networks (RNNs)
- RNN cell and model structure
- Forward and backward propagation in RNNs
- Gradient clipping
- Gated Recurrent Units (GRUs)
- Character-level language modeling
