# 📰 Fake News Detection using Machine Learning

This project implements a **Fake News Detection System** using **Python, Scikit-learn, and Natural Language Processing (NLP)**.  
It classifies news articles as **Real (True)** or **Fake** based on their textual content.  

---

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model](#model)
- [Evaluation](#evaluation)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 📖 Overview
With the rise of online media, the spread of **fake news** has become a huge problem.  
This project demonstrates how machine learning can be used to automatically classify articles as **fake** or **real** using **TF-IDF (Term Frequency–Inverse Document Frequency)** and a **Naive Bayes classifier**.

---

## 📊 Dataset
The project uses two datasets:

- **True.csv** → Contains real news articles.  
- **Fake.csv** → Contains fake news articles.  

Each dataset includes:
- `title` – Headline of the article  
- `text` – Full content of the article  
- `subject` – Category (politics, world news, etc.)  
- `date` – Date of publication  
- `label` – Added field (0 for True, 1 for Fake)  

Both datasets are combined into one DataFrame for training/testing.

---

## ⚙️ Installation

Clone this repository:

```bash
git clone <repository_url>
cd fake-news-detection
```
Install dependencies:
```bash
pip install pandas scikit-learn
```
Place datasets inside the project folder:

- **True.csv**
- **Fake.csv**

---

## 🧠 Model
- TF-IDF Vectorizer → Converts text into numerical features.
- Multinomial Naive Bayes → Probabilistic classifier suitable for text classification.

---

## 📈 Evaluation

The model is evaluated using:

- ✅ Accuracy Score – Measures overall performance.
- 📊 Classification Report – Provides precision, recall, F1-score for each class.

---

 ## 🔮 Future Improvements
- Add deep learning models (LSTM, BERT, Transformer).
- Deploy as a web app for real-time detection.
- Enhance data cleaning & preprocessing.

---

## 📜 License

This project is licensed under the MIT License – feel free to use and modify it.

## 👩‍💻 Developed by: Pragya Manna
