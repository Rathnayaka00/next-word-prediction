# Cricket Text Prediction Model

This repository contains a Next Word Prediction model that is trained on a dataset about cricket history. The model is implemented using TensorFlow and generates contextually appropriate text based on the input. 

## Features
- Preprocessing of text data with tokenization and padding.
- Model architecture includes an Embedding layer, LSTM, and a Dense output layer with softmax activation.
- Ability to generate text predictions based on given input sentences.
- Serialization and deserialization of the model and tokenizer for reuse.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/cricket-text-prediction.git
   cd cricket-text-prediction
