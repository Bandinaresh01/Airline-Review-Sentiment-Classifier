Project Name: Airline Review Sentiment Classifier

This project focuses on classifying airline review sentiments using multiple neural network architectures. It begins with a simple neural network using one-hot encoded input. It then advances to RNN and LSTM models that leverage pre-trained GloVe word embeddings for better contextual understanding.

The process includes text preprocessing, vocabulary creation, GloVe embedding matrix construction, and feeding sequences into the models. Models are trained and evaluated using standard metrics like accuracy, precision, recall, and F1-score. Finally, the model can predict the sentiment of a custom input sentence.

Technologies used: Python, PyTorch, NumPy, NLTK, GloVe embeddings.

To run: Preprocess data, train the model using train.py, and run prediction using predict.py.
