# ⚖️ Legal Chatbot 

This project is an intelligent **Legal Chatbot** designed to provide assistance with legal queries, explain legal terms, and guide users through basic legal processes. It uses natural language processing (NLP) and machine learning to understand and respond to user queries.

---

## 📖 Overview

The chatbot acts as a **virtual legal assistant**, helping users with:
- Understanding legal jargon
- Getting answers to common legal questions
- Basic guidance in civil/criminal/labor laws
- Document information like FIR, contracts, rights, etc.

---

## ✅ Features

- Pre-trained or custom-trained NLP model for intent detection
- Legal keyword search and context-based responses
- FAQs support with fallback for unknown questions

---

## 🧠 Tech Stack

- Python
- NLTK 
- scikit-learn or TensorFlow/Keras (for training models)
- Streamlit (for interface)

---

## 📂 Dataset / Knowledge Base

- Custom legal Q&A dataset or scraped information from public legal websites
- Optional: Indian Penal Code (IPC), contract law sections, rights-related info
- [Legal Text Corpora](https://www.kaggle.com/search?q=legal+text)

---

## 🛠️ Installation

Clone the repository:

git clone https://github.com/Deekshagowda25/legal-chatbot.git
cd legal-chatbot

## Install the dependencies:

pip install -r requirements.txt

## Set up environment 
export OPENAI_API_KEY=your_key_here 

## ▶️ Usage
To run the chatbot in terminal:

python chatbot.py

## To launch the web interface

streamlit run app.py
