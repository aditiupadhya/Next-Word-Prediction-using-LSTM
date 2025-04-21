# Next-Word-Prediction-using-LSTM
1. Deep Learning model to predict the next word in given sequence of words 
2. Trained model using from Shakespeare's 'Hamlet' as dataset.
3. LSTM Model with Embedding layer, 2 LSTM layers, Dense layer, output layer as Softmax activation function.
4. Initially text is tokenised, converted into sequences, padded to make uniform input length, then split sequences into train and test. 
5. To train the model, early stopping used on sequences to avoid overfitting, also checks validation loss, and when loss improves, early stopping stops training.
6. Deployed as Streamlit Web app, to predict next word for user input in real time.

<img width="275" alt="image" src="https://github.com/user-attachments/assets/a1a87d3f-ade0-4333-a7c2-15b33cec6c7b" />

