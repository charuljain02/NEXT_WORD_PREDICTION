# Next Word Prediction Using LSTM

An NLP and Deep Learning project that predicts the next word based on user input using an LSTM (Long Short-Term Memory) neural network.

## 🚀 Live Demo

**Try the application here:**  
[Next Word Prediction App](https://nextwordprediction-lmkpsdmlrdhc3dx5cjulhn.streamlit.app/)

## 📌 Project Overview

Next Word Prediction is a Natural Language Processing (NLP) project that uses a Recurrent Neural Network (RNN) architecture called LSTM to predict the next word in a given text sequence.

The model learns patterns, word sequences, and contextual relationships from text data during training. When a user enters a sequence of words, the trained model predicts the next word based on the learned patterns.

## ✨ Features

- Predicts the next word from user-provided text.
- Uses an LSTM-based deep learning model.
- Processes text using tokenization and sequence padding.
- Generates predictions based on previously learned language patterns.
- Interactive web interface built using Streamlit.
- Deployed online for easy access.

## 🛠️ Technologies Used

- **Python** – Programming language
- **TensorFlow / Keras** – Deep Learning framework
- **LSTM** – Sequence prediction model
- **NLP** – Natural Language Processing
- **NumPy** – Numerical operations
- **Streamlit** – Web application and deployment
- **Pickle** – Saving and loading preprocessing objects

## 📂 Project Structure

```text
Next_Word_Prediction/
│
├── app.py
├── lstm_model2.h5
├── tokenizer.pkl
├── max_len.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/charuljain02/NEXT_WORD_PREDICTION.git
```

### 2. Navigate to the project directory

```bash
cd NEXT_WORD_PREDICTION
```

### 3. Create a virtual environment (optional)

```bash
python -m venv tf_env
```

Activate it on Windows:

```bash
tf_env\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
streamlit run app.py
```

The application will open in your browser.

## 🧠 How It Works

1. **Text Preprocessing:** The input text is converted into tokens using a tokenizer.
2. **Sequence Preparation:** The tokenized input is padded to match the sequence length used during training.
3. **Model Prediction:** The LSTM model processes the input sequence and predicts the next word.
4. **Word Mapping:** The predicted token index is converted back into its corresponding word using the tokenizer.
5. **Output:** The predicted next word is displayed in the Streamlit application.

## 📦 Model and Preprocessing Files

- `lstm_model2.h5` – Trained LSTM model.
- `tokenizer.pkl` – Saved tokenizer used to convert words into numerical sequences.
- `max_len.pkl` – Saved maximum sequence length used during preprocessing.

These files are required to load the trained model and generate predictions without training it again.

## 🌐 Deployment

The application is deployed using **Streamlit Community Cloud**.

[Open Live Application](https://nextwordprediction-lmkpsdmlrdhc3dx5cjulhn.streamlit.app/)

## 🎯 Learning Outcomes

- Understanding Natural Language Processing fundamentals.
- Learning how tokenization and sequence padding work.
- Understanding Recurrent Neural Networks and LSTM architecture.
- Training and using a deep learning model for text prediction.
- Saving and loading trained models using TensorFlow/Keras.
- Building and deploying an interactive ML application using Streamlit.

## 👩‍💻 Author

**Charul Jain**

B.Tech – Computer Science and Engineering

[GitHub Profile](https://github.com/charuljain02)

---

⭐ If you find this project interesting, feel free to explore the repository!
