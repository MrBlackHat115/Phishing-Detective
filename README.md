# 🕵️ Phishing_Detective

Phishing_Detective is a **Natural Language Processing (NLP) phishing email detection system** that analyzes email text to identify characteristics commonly associated with phishing and social engineering attacks.  
The project combines **rule-based NLP techniques**, **linguistic analysis**, and a **pretrained transformer model (BERT)** to classify emails as phishing or legitimate.

---

## 🚀 Features

- Email text cleaning and normalization
- Tokenization, stopword removal, and lemmatization
- Part-of-Speech (POS) tagging using spaCy
- Phishing keyword detection and frequency analysis
- Rule-based sentiment analysis using VADER
- Transformer-based phishing classification using Hugging Face
- Visualizations for keyword frequency and sentiment distribution
- Modular, easy-to-extend pipeline

---

## 🧠 Technologies Used

- **Python**
- **Pandas**
- **NLTK**
- **spaCy**
- **CleanText**
- **Matplotlib**
- **Hugging Face Transformers**
- **PyTorch**

---

## 📂 Project Structure

```text
Phishing_Detective/
│
├── emails.csv                   # Input email dataset
├── phishing_keywords.txt         # List of phishing-related keywords
├── phishing_detective.ipynb      # Main analysis notebook
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
