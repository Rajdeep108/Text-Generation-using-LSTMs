# Text-Generation-using-LSTMs
This project utilizes a Long Short-Term Memory (LSTM) neural network to generate text based on a provided dataset. The process begins by loading a text file and preprocessing the data by converting it to lowercase and extracting unique characters. The notebook constructs input-output sequences, where each input is a substring of 200 characters, and the output is the subsequent character.

The characters are mapped to integers, allowing the model to learn their relationships through a one-hot encoding scheme. An LSTM model is then defined using PyTorch, comprising multiple layers with dropout for regularization. After setting up the model, it is trained over several epochs, optimizing the loss function via backpropagation.

Finally, the trained model generates text by predicting the next characters based on a random initial sequence, demonstrating the capability to produce coherent text that mimics the style of the original dataset.

