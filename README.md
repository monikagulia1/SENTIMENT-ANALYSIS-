# SENTIMENT ANALYSIS on Product Reviews 📊📝
This project demonstrates the power of NLP in sentiment analysis by preprocessing text data, balancing the dataset, and evaluating model performance.

Overview 🌟
This project aims to classify sentiment (positive, negative, neutral) in product reviews using Natural Language Processing (NLP). We focus on handling class imbalance, text cleaning, and using VADER for sentiment classification, with an emphasis on improving model performance for accurate sentiment prediction.

Features ⚙️
  Sentiment Classification: Classifies reviews into positive, negative, or neutral categories based on the content of the review text. 💬
  Data Cleaning: Removes unwanted characters, stopwords, and applies other preprocessing steps to prepare the data for analysis. 🧹
  SMOTE: Handles class imbalance by generating synthetic examples for underrepresented classes. ⚖️
  Model Evaluation: Uses various evaluation metrics, including precision, recall, and F1 score to assess model performance. 📈

Key Insights 💡
  Stopword Handling: Manually check stopwords, as some common stopwords can carry negative sentiment in reviews. Avoiding stopwords improves sentiment analysis. 🚫
  Neutral Reviews: Many neutral reviews contain constructive criticism, which can be valuable feedback for sellers. 🛠️
  Instrument-Specific Reviews: The dataset primarily focuses on string instruments, such as guitars. 🎸
  Data Balancing: Balancing the dataset using SMOTE improved recall, F1 score, and overall model performance. 🔄
  Performance Metrics: A high F1 score of 94% indicates successful sentiment classification. 🎯

Tools & Libraries Used 🛠️
VADER: For sentiment analysis based on lexicon rules. 📚
Python Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `SMOTE` (from `imblearn`). 📊
Data Preprocessing: Tokenization, stopword removal, and vectorization (e.g., TF-IDF). 🔄
Model Evaluation: Precision, recall, F1 score, and confusion matrix for performance analysis. 📊

Conclusion 🏆
This project demonstrates the power of NLP in sentiment analysis by preprocessing text data, balancing the dataset, and evaluating model performance. Through these steps, we achieved an impressive F1 score of 94%, showcasing the effectiveness of the sentiment classification model. ✅

