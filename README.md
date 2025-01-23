Sentiment Clustering with K-Means
Overview:
This project processes and clusters text data into sentiment categories (positive, negative, neutral) using unsupervised learning. It leverages natural language processing (NLP) techniques for text preprocessing and applies the K-Means clustering algorithm for sentiment analysis.

Features:
Text Preprocessing:

Converts text to lowercase, tokenizes, removes stopwords, and performs lemmatization using NLTK.
TF-IDF Vectorization:

Transforms preprocessed text into numerical features using TF-IDF for clustering.
K-Means Clustering:

Groups text data into three sentiment categories.
Sentiment Assignment:

Maps clusters to sentiment labels: positive, negative, and neutral.
Dependencies:
pandas for data handling.
nltk for NLP preprocessing.
scikit-learn for TF-IDF vectorization and K-Means clustering.
Prerequisites:
Install required libraries:
bash
Copy
Edit
pip install pandas scikit-learn nltk
Download NLTK resources:
python
Copy
Edit
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
How to Use:
Place the dataset (Dataset_3.5k.xlsx) in the specified path.
Run the script to preprocess the text, vectorize it, and perform clustering.
Analyze the output: a DataFrame with titles and their assigned sentiment labels.
