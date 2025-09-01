# Autoregression.ipynb

This project demonstrates text generation using a neural language model.

We train a model on a text dataset and use it to generate new text sequences given a seed prompt. The generation process leverages a temperature-based sampling strategy, where the temperature parameter controls the creativity of the model:

Low temperature → safer, more predictable text.

High temperature → more diverse, creative, but sometimes less coherent text.

The notebook includes:

Preprocessing the text dataset.

Training an autoregressive model.

Implementing a custom text generation function.

Experimenting with temperature-based decoding strategies.
