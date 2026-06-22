# 📌 AI-Powered Paraphrasing Tool

## 🚀 Overview

This project is an AI-based Natural Language Processing (NLP) system that performs intelligent text paraphrasing using Transformer models. It also includes grammar correction and automatic evaluation of output quality using NLP metrics.

The system is built as a complete NLP pipeline combining:

- 🤖 Transformer-based deep learning (T5 model)
- ✍️ Grammar correction system
- 📊 NLP evaluation metrics
- 🧠 Semantic similarity analysis
- 💬 Interactive console mode

---

## ✨ Features

### 🧠 1. AI Paraphrasing (T5 Model)
- Uses Hugging Face Transformer model:  
  ramsrigouthamg/t5_paraphraser
- Generates high-quality paraphrases using beam search
- Maintains meaning while changing sentence structure

---

### ✍️ 2. Grammar Correction
- Uses LanguageTool / TextBlob-style correction
- Detects grammatical errors
- Automatically corrects generated paraphrases
- Reports number of issues fixed

---

### 📊 3. Evaluation System

The system evaluates paraphrases using 3 NLP metrics:

- **BLEU Score** → Measures word overlap accuracy  
- **ROUGE-L Score** → Measures sequence similarity  
- **Semantic Similarity** → Measures meaning preservation (most important)

---

## ⚙️ Technologies Used

- Python 🐍
- Hugging Face Transformers 🤗
- T5 Paraphrasing Model
- Sentence Transformers
- NLTK
- ROUGE Score
- LanguageTool / TextBlob
- PyTorch

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/paraphrasing-tool.git
cd paraphrasing-tool
```

### 2. Install dependencies
```bash
pip install transformers sentencepiece torch
pip install textblob nltk rouge-score sentence-transformers
pip install language-tool-python
```

---

## ▶️ How to Run

```bash
python paraphraser.py
```

---

## 🧠 How It Works (Pipeline)

Input Text
   ↓
T5 Transformer Model (Paraphrasing)
   ↓
Grammar Checker (TextBlob / LanguageTool)
   ↓
Evaluation Metrics:
   ├── BLEU Score
   ├── ROUGE-L Score
   └── Semantic Similarity
   ↓
Final Output + Analysis Report

---

## 📁 Project Structure

paraphrasing-tool/
│
├── paraphraser.py        # Main Python script (FULL PIPELINE)
├── README.md             # Project documentation
├── requirements.txt      # Dependencies
└── LICENSE               # License file

---

## 📊 Example Output

Input:
Machine learning enables computers to learn from data and make accurate predictions without being explicitly programmed.

Output:
AI systems allow machines to learn patterns from data and generate predictions without manual programming.

Evaluation:
BLEU Score          : 0.52
ROUGE-L Score       : 0.61
Semantic Similarity : 0.89

---

## 🎯 Use Cases

- NLP learning projects
- AI writing assistants
- Academic paraphrasing tools
- Content rewriting systems
- Research experiments in NLP

---

## 👩‍💻 Author

Jincy Jos

---

## 📜 License

MIT License
