# NLP Preprocessing Pipeline (Google colab)

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
- **Sentiment Analysis:** "not good" → removing *not* changes meaning  
- **Question Systems:** removing *what, how* affects intent  

### Stemming vs Lemmatization
- **Stemming:** running → runn  
- **Lemmatization:** running → run  

---

## ✅2: Preprocessing Function
Includes:
- Lowercasing  
- URL & email removal  
- Number removal  
- Repeated character handling  
- Punctuation removal  
- Tokenization  
- Short word filtering  

---

## ✅3: Stress Testing
Tested on:
- Emojis  
- URLs  
- Numbers  
- Spam text  

---

## ✅4: Token Analytics
- Total tokens  
- Unique tokens  
- Average token length  

---

## ✅5: Frequency Analysis
- Top frequent words  
- Least frequent words  

---

## ✅6: Full Pipeline
Returns:
- All tokens  
- Cleaned sentences  

---

## ✅7: Error Handling
Handles:
- Empty string  
- Only emojis  
- Only numbers  

---

## 🚀 How to Run

1. Open Google Colab:
2. Open the file:
IN226038102_Task1_NLP_Preprocessing_Engine.ipynb
3. Run all cells

🔥 Key Highlights
End-to-end NLP pipeline
Works on noisy real-world data
Handles edge cases
Clean and modular implementation
