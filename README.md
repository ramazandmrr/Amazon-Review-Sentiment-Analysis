# 🛒 Kozmos Amazon Review Sentiment Analysis

This project applies **Natural Language Processing (NLP)** and **Logistic Regression** to perform sentiment analysis on Amazon product reviews.  

## 📂 Dataset
- 5611 reviews  
- Variables: `Star`, `HelpFul`, `Title`, `Review`  

## 🚀 Steps
1. **Text Preprocessing:** Lowercasing, removing punctuation/numbers, removing stopwords, lemmatization  
2. **Visualization:** Word frequency barplot, WordCloud  
3. **Sentiment Analysis:** `SentimentIntensityAnalyzer` → positive / negative labeling  
4. **Machine Learning:** TF-IDF + Logistic Regression, accuracy evaluation and reporting  
5. **Prediction:** Randomly sampled review classified with the model  

## 🛠 Technologies
Python, Pandas, NLTK, Scikit-learn, Matplotlib, WordCloud  

## 📊 Results
- Reviews labeled as **positive/negative**  
- Logistic Regression model achieved successful classification  
- Visualizations highlighted key customer feedback patterns  
