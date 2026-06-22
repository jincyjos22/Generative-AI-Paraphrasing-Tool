📌 AI-Powered Paraphrasing Tool
🚀 Overview

This project is an AI-based Natural Language Processing (NLP) system that performs intelligent text paraphrasing using Transformer models. It also includes grammar correction and automatic evaluation of output quality using NLP metrics.

It is designed as a complete NLP mini-project combining:

Deep Learning (Transformers)
NLP preprocessing
Text evaluation metrics
Grammar correction system
✨ Key Features
🧠 1. AI Paraphrasing
Uses T5 Transformer model
Generates multiple paraphrased versions of input text
Maintains original meaning while changing structure
✍️ 2. Grammar Correction
Uses LanguageTool
Detects grammatical errors
Provides corrected output text
📊 3. Evaluation System

Automatically evaluates paraphrases using:

BLEU Score → Word overlap accuracy
ROUGE-L Score → Sequence similarity
Semantic Similarity → Meaning preservation (Sentence Transformers)
⚙️ Technologies Used
Python 🐍
Hugging Face Transformers 🤗
T5 Model (ramsrigouthamg/t5_paraphraser)
Sentence Transformers
NLTK
ROUGE Score
LanguageTool
TextBlob (optional usage)
📦 Installation
1. Clone the repository
git clone https://github.com/your-username/paraphrasing-tool.git
cd paraphrasing-tool
2. Install dependencies
pip install -r requirements.txt

OR manually:

pip install transformers sentencepiece torch
pip install nltk textblob rouge-score sentence-transformers language-tool-python
▶️ How to Run
python paraphraser.py
📁 Project Structure
paraphrasing-tool/
│
├── paraphraser.py        # Main Python script
├── README.md             # Project documentation
├── requirements.txt      # Dependencies
└── LICENSE               # License file
🔄 Workflow
Input Text
   ↓
T5 Model (Paraphrasing)
   ↓
Grammar Checker (LanguageTool)
   ↓
Evaluation Metrics:
   - BLEU Score
   - ROUGE-L Score
   - Semantic Similarity
   ↓
Final Output + Report
📊 Example Output
Input:
Machine learning enables computers to learn from data.
Output:
AI systems allow machines to learn patterns from data.
Evaluation:
BLEU: 0.52
ROUGE-L: 0.61
Semantic Similarity: 0.89
🎯 Use Cases
NLP learning projects
AI paraphrasing tools
Academic writing assistance
Content rephrasing systems
Research experiments
📌 Requirements

Create requirements.txt:

transformers
sentencepiece
torch
nltk
textblob
rouge-score
sentence-transformers
language-tool-python
👩‍💻 Author

Jincy Jos

📜 License

This project is licensed under the MIT License.

