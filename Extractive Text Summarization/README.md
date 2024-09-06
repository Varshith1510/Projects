# Article Summarization

  This repository contains a Python implementation of the Text Rank algorithm, inspired by Google's Page Rank algorithm, specifically for summarizing non-premium articles on Medium.

## Features:
- Fetches the content of the provided Medium article.
- Processes the text to identify the most important sentences.
- Ranks these sentences using the Text Rank algorithm.
- Generates a concise summary based on the highest-ranked sentences.

## How It Works:

1. **Data Preparation:**
   - Extract data from the Medium article and store it in a text file.
   - Read the file, process the text using NLP techniques such as tokenization, stopwords removal & lemmatization.

2. **Feature Representation:**
   - Fast Text word embeddings are created

3. **Calculate Similarity:**
   - Use text similarity function to compute the similarity scores between the fast text vectors.

4. **Generate Summary:**
   - Apply Page Rank algorithm and sort the sentences based on their importance(no. of connections).
   - Pick the first n sentences to summarize the data
