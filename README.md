
# Next Word Predictor using LSTM

This project implements a **Next Word Prediction** model using **LSTM (Long Short-Term Memory)** networks in TensorFlow/Keras. It is trained on a sample text corpus to predict the next likely word given a sequence of words.

## 🚀 Project Overview

Natural Language Processing (NLP) has many practical applications, and predicting the next word is a fundamental task in language modeling. This project explores sequence modeling using LSTM, a type of recurrent neural network (RNN), to build a simple yet effective next-word predictor.

## 🧠 Model Architecture

- **Tokenizer**: Keras `Tokenizer` to vectorize text and generate sequences.
- **Input Preparation**: Sequence generation using n-gram technique.
- **Neural Network**: A stacked LSTM model with embedding and dense layers.
- **Loss Function**: Categorical crossentropy.
- **Optimizer**: Adam optimizer.

## 📁 Project Structure

```bash
next_word_predictor_using_lstm/
│
├── Copy_of_lstm_project.ipynb     # Main Jupyter Notebook with model training and prediction
├── README.md                      # Project documentation
````

## 📊 Dataset

The model is trained on a small sample text corpus for demonstration purposes. You can replace the training data with any large corpus (e.g., Wikipedia dumps, books) to enhance performance.

## 📈 Training Process

1. Tokenization of input text
2. Generation of sequences with n-gram modeling
3. Padding sequences to uniform length
4. Model definition with LSTM layers
5. Model training and evaluation
6. Word prediction based on seed text

## 🔍 Sample Usage

After training, use the model to generate predictions:

```python
seed_text = "It is a beautiful"
next_words = 3

# Predict next words based on seed text
predict_next_words(seed_text, next_words, model, tokenizer, max_sequence_len)
```

## ✅ Requirements

* Python 3.x
* TensorFlow
* Keras
* NumPy

Install requirements:

```bash
pip install tensorflow numpy
```

## 📌 Notes

* This model performs best with a large and clean dataset.
* Training time and accuracy depend on the volume and quality of data.

## 🧑‍💻 Author

**Haseeb Ul Hassan**

## 📜 License

This project is licensed under the MIT License.

```

---

Would you like me to help you improve or refactor the code in the notebook as well?
```
