# 🕵️ Phishing_Detective


**Phishing_Detective** is a **Natural Language Processing (NLP)–based phishing email detection system** that analyzes email text to identify characteristics commonly associated with phishing and social engineering attacks.

The project combines **rule-based NLP preprocessing and linguistic analysis** with a **pretrained transformer-based phishing detection model** (`ealvaradob/bert-finetuned-phishing`) to classify emails as phishing or legitimate. Traditional NLP techniques, such as text cleaning, tokenization, stopword removal, lemmatization, part-of-speech (POS) tagging, keyword frequency analysis, and sentiment scoring, are used to extract interpretable features from email content.

To complement these explainable features, a **fine-tuned BERT model** is applied for contextual classification, allowing the system to capture semantic patterns that rule-based methods alone may miss.

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
```

## (Recommended) Create a Virtual Environment
```bash
- python -m venv venv
```

## Activate the environment

- Linux / macOS:
```bash
source venv/bin/activate
```

Windows:
```
venv\Scripts\activate
```

## Install Dependencies
```bash
pip install -r requirements.txt
```
