# 🚀 LSTM Next Word Prediction

## 📖 Description
This project is an implementation of an LSTM-based neural network to predict the next word in a given sentence. The dataset used for training is Shakespeare's *Hamlet*, sourced from the NLTK Gutenberg corpus. 

---

## 🎯 Objective
The goal of this project is to predict the next word in a given sentence using an LSTM-based neural network.

---

## 🏗️ Model Architecture
- **Embedding Layer**: Converts words into dense vectors of fixed size (100 dimensions).
- **LSTM Layer 1**: 150 units.
- **Dropout Layer**: 20% dropout to prevent overfitting.
- **LSTM Layer 2**: 100 units.
- **Dense Layer**: Output layer with `softmax` activation for multi-class word prediction.

---

## 📊 Dataset
- **Source**: Gutenberg Corpus (*shakespeare-hamlet.txt*)
- **Preprocessing**:
  - Tokenization using TensorFlow's `Tokenizer`.
  - Padding sequences for uniform input length.
  - Splitting data into training and validation sets.

---

## 🚀 Deployment
- **Framework**: Streamlit
- **Usage**: Deployed as a web application where users can input a sentence to receive predicted next words.

🔗 [Live Demo](https://github.com/pranav6905/LSTM_nextWord)

---

## 📈 Performance
- **Training Accuracy**: 66.69%
- **Validation Accuracy**: 4.53%
- The model struggles with generalization beyond the training data.

