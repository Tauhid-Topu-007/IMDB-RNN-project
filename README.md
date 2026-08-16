# 🎬 IMDB Sentiment Analysis with SimpleRNN

A deep learning project for **binary sentiment analysis of IMDB movie reviews** using TensorFlow/Keras and a SimpleRNN architecture. The model processes review text and predicts whether the sentiment is **Positive** or **Negative**.

## 🚀 Project Highlights

- Text sentiment classification using a SimpleRNN
- IMDB movie-review dataset from TensorFlow/Keras
- Word-index encoding and sequence padding
- Embedding layer for learning word representations
- Pre-trained `.h5` model for inference
- Interactive Streamlit application
- Jupyter notebooks for embedding, training, and prediction experiments

## 🧠 Model Architecture

```text
Movie Review
     ↓
IMDB Word Index
     ↓
Sequence Encoding
     ↓
Padding (max length = 500)
     ↓
Embedding Layer
     ↓
SimpleRNN
     ↓
Dense + Sigmoid
     ↓
Positive / Negative
```

## 📁 Project Structure

```text
IMDB-RNN-project/
├── SimpleRNN/
│   ├── embedding.ipynb
│   ├── main.py
│   ├── prediction.ipynb
│   ├── simplernn.ipynb
│   └── simple_rnn_imdb.h5
├── requirements.txt
└── README.md
```

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- TensorBoard
- Streamlit

The required packages are listed in `requirements.txt`. fileciteturn12file0

## ⚙️ Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/Tauhid-Topu-007/IMDB-RNN-project.git
cd IMDB-RNN-project
pip install -r requirements.txt
```

## ▶️ Run the Streamlit App

From the `SimpleRNN` directory:

```bash
cd SimpleRNN
streamlit run main.py
```

Enter a movie review in the text box and click **Classify** to receive the predicted sentiment and prediction score. The application loads the saved `simple_rnn_imdb.h5` model and preprocesses reviews using the IMDB word index. fileciteturn13file0

## 🔬 Learning Objectives

This project demonstrates practical concepts in:

- Natural Language Processing (NLP)
- Text preprocessing and tokenization
- Word embeddings
- Sequence modeling
- Recurrent Neural Networks
- Binary sentiment classification
- Model saving and loading
- Deploying ML models with Streamlit

## 📊 Dataset

The project uses the **IMDB movie review dataset** available through `tensorflow.keras.datasets.imdb`. Reviews are represented as integer sequences based on the IMDB vocabulary and padded to a fixed length before inference.

## 🔮 Future Improvements

- Compare SimpleRNN with LSTM and GRU
- Add accuracy/loss and confusion-matrix visualizations
- Improve text preprocessing
- Add model evaluation metrics such as Precision, Recall, and F1-score
- Deploy the Streamlit application publicly

## 👨‍💻 Author

**Tauhidul Islam Topu**

GitHub: https://github.com/Tauhid-Topu-007

---

⭐ If you find this project useful, consider giving the repository a star!