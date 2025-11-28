# Sentiment-Analysis-Using-SVM-and-NB-
This project performs sentiment classification on Amazon reviews from the Cell Phones & Accessories category. Using NLP preprocessing, TF-IDF, POS tagging, and lexicon-based features, two machine learning models—Multinomial Naïve Bayes and Linear SVC—are trained to classify reviews as positive, negative, or neutral. An interactive Power BI dashboard is also developed to visualize customer insights and sentiment trends.

# 🚀 Project Objectives
1. Analyze Amazon review patterns using NLP techniques
2. Build and compare machine learning models for sentiment classification
3. Visualize insights using an interactive Power BI dashboard

# 📦 Dataset
1. Source: Amazon Product Reviews (Cell Phones & Accessories)
2. Format: JSON
3. Contains review text, rating, metadata, and helpfulness information

#🧹 Data Preprocessing
1. Text cleaning (lowercasing, punctuation removal, lemmatization)
2. Stop-word removal and tokenization
3. Sentiment labeling (VADER & TextBlob comparison)
4. Handling class imbalance

# 🧠 Feature Engineering
1. TF-IDF with uni/bi-grams
2. Part-of-Speech (POS) features
3. Polarity lexicon counts
4. Review-based metadata (length, helpfulness, etc.)
5. Chi-Square feature selection

# 🤖 Machine Learning Models
1. Linear SVC
Accuracy: 95%
F1-Score: 0.816
Best overall performance

3. Multinomial Naïve Bayes
Accuracy: 82%
F1-Score: 0.816

📊 Dashboard (Power BI)
1. The Power BI dashboard visualizes:
2. Sentiment distribution
3. Top frequent words
4. Brand-level sentiment comparison
5. Review trends and insights

# 🛠️ Technologies Used
1. Python
2. Scikit-learn
3. NLTK / TextBlob / VADER
4. Pandas, NumPy
5. Power BI
