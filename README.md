# Next-Word-Prediction-using-LSTM
Deep Learning model to predict the next word in given sequence of words 
Trained model using from Shakespeare's 'Hamlet' as dataset.
LSTM Model with Embedding layer, 2 LSTM layers, Dense layer, output layer as Softmax activation function.
Initially text is tokenised, converted into sequences, padded to make uniform input length, then split sequences into train and test. 
To train the model, early stopping used on sequences to avoid overfitting, also checks validation loss, and when loss improves, early stopping stops training.
Deployed as Streamlit Web app, to predict next word for user input in real time.
