# Agribot
A Multilingual Chatbot for farmers
# 🌾 AgriBot – A Multilingual Chatbot for Indian Farmers

AgriBot is a multilingual chatbot designed to empower Indian farmers by providing instant, reliable agricultural information in **Hindi**, **English**, and **Punjabi**. It aims to break language barriers and make essential farming knowledge accessible to rural communities across India.

## Flow Diagram
<img width="767" height="688" alt="image" src="https://github.com/user-attachments/assets/85db3f99-99b8-4855-a5fd-3ebb1260404a" />

---

## 🧠 Features

- 🌐 **Multilingual Support**: Understands and responds in Hindi, English, and Punjabi using Neural Machine Translation.
- 📊 **Covers Key Topics**:
  - Crop management
  - Pest control
  - Weather updates
  - Government schemes
  - Market prices
- 🤖 **Natural Language Understanding** using NLP techniques.
- ⚙️ **Real-time Translations** powered by Google Translate API.

---

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Frontend**: HTML, CSS, JavaScript
- **Translation & NLP**: Googletrans, Regular Expressions, Word-overlap Matching

---

## 🚀 Methodology

1. **Dataset Parsing**: Loads Q&A pairs from a JSONL file for agricultural queries.
2. **Language Detection**: Identifies if the user input is in Hindi, English, or Punjabi.
3. **Text Normalization**: Preprocesses input by removing special characters, lowercasing, etc.
4. **Query Matching**: Matches user query to dataset using word-overlap.
5. **Response Retrieval**: Returns the closest matching answer in the appropriate language.

---

## 📈 Evaluation Metrics

- **BLEU Score**: For translation accuracy.
- **Precision, Recall, F1-Score**: For model performance assessment.

---

## 🚧 Challenges Faced

- Difficulty training custom multilingual models due to:
  - Lack of high-quality domain-specific data
  - Resource constraints
  - Complexity of grammar/cultural nuances in translation
- Initial issues with tools like LangDetect and SentenceTransformers

---

## ✅ Final Implementation

Switched to **Google Translate’s NMT models**, which provide:
- Context-aware, high-quality translations
- Scalability
- Reduced training complexity

---

## 📷 UI Screenshots

- English, Hindi, and Punjabi prompts supported via web interface.

---

## 🔭 Future Scope

- 🎙️ Add voice-to-text input
- 🌿 Train agriculture-specific language models
- 📥 Implement user feedback loop for better response accuracy

---

## 📚 References

1. [IEEE: An AgroBot Chatbot for Farmers](https://ieeexplore.ieee.org/document/10276356)
2. [Agrobot NLP Paper (UCoE)](https://universalcollegeofengineering.edu.in)
3. [IRJET Agrobot Paper](https://d1wqtxts1xzle7.cloudfront.net/90575477/IRJET_V9I4393-libre.pdf)
4. [NLP-based Agriculture Chatbot (IEEE)](https://ieeexplore.ieee.org/abstract/document/10306512)

---

> This project showcases the power of combining NLP with NMT to support real-world, multilingual applications in agriculture.
