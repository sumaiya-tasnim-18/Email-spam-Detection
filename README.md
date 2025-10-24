# 📩EMAIL_SPAM_DETECTION – Using Machine Learning
This repository demonstrates a machine learning workflow for detecting and classifying emails as spam or ham (non-spam). It leverages text preprocessing, natural language processing (NLP), and the Multinomial Naive Bayes model to identify unsolicited or phishing content efficiently.

# 📇 Project Overview
    •Dataset: spam.csv containing labeled email messages (ham and spam)
    •Tools: Python (pandas, numpy, matplotlib, seaborn, scikit-learn, nltk, wordcloud)
    •Focus Areas: Text preprocessing, NLP-based feature extraction (TF-IDF), model training with Multinomial Naive Bayes, evaluation metrics, and result visualization

# ╰┈➤📝 Steps Breakdown
    •Step 1: Loaded and inspected the dataset, removed unnecessary columns, and renamed headers for consistency.
    •Step 2: Preprocessed email text by converting to lowercase, removing punctuation, stopwords, and applying stemming for clean feature extraction.
    •Step 3: Transformed text data using TF-IDF vectorization and split the dataset into training and testing sets.
    •Step 4: Trained a Multinomial Naive Bayes model to classify emails as spam or ham.
    •Step 5: Evaluated the model using accuracy (97.8%), confusion matrix, and classification report (precision, recall, F1-score).
    •Step 6: Created visual insights including class distribution, confusion matrix heatmap, word clouds, top frequent words, email length distribution, and spam-ham ratio pie chart.

# 🎯 Outcome
Developed a Multinomial Naive Bayes model that achieved 97.8% accuracy in distinguishing spam from ham emails. The project demonstrates the power of NLP and machine learning for text classification, supported by comprehensive visual analytics for model interpretability and dataset insights.

# 📌Project Insights:
<img width="1790" height="2285" alt="image" src="https://github.com/user-attachments/assets/af78c04b-9dbb-4e9f-88ef-f96d627c60ea" />
