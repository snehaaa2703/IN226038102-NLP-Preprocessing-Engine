# NLP Preprocessing Pipeline

## 📌 Overview
This tasks implements a complete **NLP preprocessing pipeline** including text cleaning, tokenization, stress testing, token analytics, and frequency analysis.

---

## ✅ 1: Conceptual Understanding

### Difference between "Love" and "love"
In NLP, they are treated as different tokens due to case sensitivity unless normalization (lowercasing) is applied.

### What happens if stopwords are not removed?
- Introduces noise in data  
- Common words like *is, the, at* dominate  
- Reduces model efficiency and accuracy  

### When removing stopwords is harmful
- **Sentiment Analysis:**  
  Example: *"not good"* → removing *not* changes meaning  
- **Question Systems:**  
  Words like *what, how* are important for intent  

### Stemming vs Lemmatization
- **Stemming:** cuts words → *running → runn*  
- **Lemmatization:** meaningful root → *running → run*  

---

## ✅2: Preprocessing Function

### Features
- Lowercasing
- URL & email removal
- Number removal
- Repeated character normalization
- Punctuation removal
- Tokenization
- Short word filtering (except *no, not*)
