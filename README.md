# Super-Hero-Name-Generator-Using-TensorFlow-
A convolutional Neural network that is trained on superheroes names and that generate name of a superhero from single character by predicting the next character and then generates the final name  

This notebook demonstrates how to build a character-level recurrent neural network (RNN) using TensorFlow/Keras to generate superhero and supervillain names based on a dataset.

The notebook covers the following steps:

Data Import and Preparation: Loading the dataset and preparing it for training, including tokenization and sequence padding.
Model Creation: Defining a sequential Keras model with Embedding, Conv1D, MaxPooling1D, LSTM, and Dense layers.
Model Training: Training the model on the prepared data.
Model Saving and Loading: Saving the trained model and demonstrating how to load it.
Name Generation GUI: Creating a basic graphical user interface (GUI) using Gradio to interactively generate names using the trained model.
This project can be used as a portfolio piece to showcase skills in natural language processing, deep learning with TensorFlow/Keras, and building simple interactive applications.
