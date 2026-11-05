# IMDb Sentiment Analysis using RNN & LSTM 

##  Description
A Natural Language Processing (NLP) project focused on classifying movie reviews from the IMDb dataset as positive or negative. This project explores the effectiveness of various Recurrent Neural Network (RNN) architectures in sequence modeling and sentiment prediction, comparing their performance to find the optimal solution.

##  Technologies
- **Language:** Python
- **Deep Learning Framework:** TensorFlow / Keras (Embedding, SimpleRNN, LSTM, Bidirectional)
- **Data Preprocessing:** Keras `pad_sequences`
- **Data Visualization:** Matplotlib
- **Environment:** Google Colab

##  Functionality
- **Data Preprocessing:** Loads the IMDb dataset (restricted to the top 10,000 words) and pads sequences to a uniform length of 500 tokens for neural network input.
- **Multi-Model Implementation:** Builds, trains, and evaluates four distinct sequential models:
  - **SimpleRNN:** A baseline recurrent model.
  - **LSTM:** A Long Short-Term Memory network to handle vanishing gradients.
  - **Bidirectional LSTM:** Processes sequences in both forward and backward directions to capture broader context.
  - **Deep LSTM:** A stacked architecture with multiple LSTM layers for learning complex hierarchical dependencies.
- **Model Evaluation & Comparison:** Analyzes test accuracy and loss across all architectures. The Deep LSTM model achieved the highest accuracy (87.06%).
- **Performance Visualization:** Generates comprehensive subplots comparing training and validation accuracy/loss for all four models side-by-side.

