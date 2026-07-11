# Sentiment-Analysis
Sentiment-Analysis

Loading and Preprocessing We will clean the text by converting to lowercase, removing special characters, and filtering out stopwords.

Cleaning: Removes noise like punctuation which doesn't contribute to sentiment. Stopwords Removal: Removes common words (e.g., 'the', 'is') to focus on meaningful tokens. 

Tokenization: Breaking text into individual words for the vectorizer.

Feature Extraction 

We use TfidfVectorizer to convert text to numerical features. TF-IDF (Term Frequency-Inverse Document Frequency) assigns higher weights to words that are unique to specific documents, helping the model identify descriptive emotion-carrying words.

Model Development & Evaluation 

We train Naive Bayes (fast, probabilistic) and Support Vector Machine (effective in high-dimensional spaces) and compare them using Accuracy and F1-Score.
