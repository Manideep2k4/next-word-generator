Next Word Generator
The Next Word Generator is an NLP-based project that predicts the next word in a sequence using an LSTM (Long Short-Term Memory) model. The model is trained on a dataset of Medium article titles to learn word patterns and generate contextually relevant predictions.

Features
Uses LSTM with an Embedding layer for sequence modeling.
Trained on real-world text data (Medium article titles).
Handles out-of-vocabulary (OOV) words using a tokenizer.
Generates predictions based on given input text.
Dataset
The project uses a dataset of Medium article titles (medium_data.csv). The text data is cleaned, tokenized, and converted into n-gram sequences for model training.

Model Architecture
Embedding Layer: Converts words into dense vector representations.
LSTM Layer: Captures sequential patterns in text.
Dropout Layer: Prevents overfitting.
Dense Layer (Softmax Activation): Predicts the most probable next word.
Technologies Used
Python
TensorFlow / Keras
NumPy, Pandas
Matplotlib (for accuracy visualization)
