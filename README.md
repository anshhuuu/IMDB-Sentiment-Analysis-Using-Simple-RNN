# IMDB-Sentiment-Analysis-Using-Simple-RNN
A sentiment analysis app using a Recurrent Neural Network (SimpleRNN) trained on the IMDB movie review dataset. Includes a Streamlit web interface for real-time prediction and user interaction.


## 🛠️ Tech Stack

- Python
- TensorFlow / Keras (SimpleRNN)
- NumPy, Pandas
- Scikit-learn
- NLTK (optional for text preprocessing)
- Streamlit

---

## ✨ Features

- Classifies IMDB-style reviews into Positive or Negative
- Uses SimpleRNN for sequence learning
- Real-time user input and prediction via Streamlit
- Probability score for prediction confidence
- Pre-trained on standard IMDB dataset (25,000 labeled reviews)

---

## ⚙️ How It Works

1. Load and preprocess the IMDB dataset.
2. Tokenize and pad review texts for RNN input.
3. Build a SimpleRNN model using Keras:
   - Embedding layer
   - SimpleRNN layer
   - Dense output with sigmoid activation
4. Train the model and evaluate accuracy.
5. Save the trained model.
6. Build a Streamlit app to accept user input and return predictions.

---

## 🧩 Installation

```bash
git clone https://github.com/anshhuuu/IMDB-Sentiment-Analysis-Using-Simple-RNN.git
cd IMDB-Sentiment-Analysis-Using-Simple-RNN
pip install -r requirements.txt

```

## Usage

```bash
streamlit run app.py

```

## Project Structure

```bash
IMDB-Sentiment-Analysis-Using-Simple-RNN/
│
├── simple_rnn.ipynb         
├── prediction.ipynb          
├── main.py                  
├── imdb_rnn_model.h5         
├── requirements.txt          
└── README.md                 

