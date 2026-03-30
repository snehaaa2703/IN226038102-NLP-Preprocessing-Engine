# Sentiment Analysis using NLP & Machine Learning (Google Colab)

## 📌 Overview
This project implements a complete **Sentiment Analysis pipeline** using NLP preprocessing and ML models on the IMDB dataset.

---

## 📂 Dataset
- IMDB Movie Reviews Dataset  
- 50,000 reviews (balanced dataset)  
- Positive → 1 | Negative → 0  

---

## 🔧 Tools & Libraries
- Google Colab  
- pandas, numpy  
- nltk  
- scikit-learn  

---

## ✅ Steps Performed

### 1. Data Loading
- Loaded dataset using pandas  
- Checked null values  
- Converted labels to numeric  

---

### 2. NLP Preprocessing
- Lowercasing  
- Removing URLs & special characters  
- Stopword removal  
- Lemmatization  

---

### 3. Feature Engineering
- Bag of Words (BoW)  
- TF-IDF  

---

### 4. Model Training
- Logistic Regression  
- Naive Bayes  
- Decision Tree  

---

### 5. Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

## 📊 Results

| Model                | Method  | Accuracy |
|---------------------|--------|----------|
| Logistic Regression | TF-IDF | 0.8893   |
| Naive Bayes         | BoW    | 0.8501   |
| Decision Tree       | BoW    | 0.714    |

---

## 🔍 Insights
- TF-IDF outperforms BoW  
- Logistic Regression gives best accuracy  
- Naive Bayes is fast but less accurate  
- Decision Tree overfits on text data  

---

## 🏆 Conclusion
**Best Model: TF-IDF + Logistic Regression**

---

## 🚀 How to Run (Google Colab)

1. Open Google Colab  
2. Upload the notebook  
3. Upload dataset file (`IMDB Dataset.csv`)  
4. Run all cells  

---

## 🔥 Key Highlights
- Built using Google Colab  
- End-to-end NLP pipeline  
- Real-world dataset  
- Model comparison included  
