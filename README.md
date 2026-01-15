# -Consumer-Complaints-Exploratory-NLP-Analysis-Python-
This project performs an exploratory Natural Language Processing (NLP) analysis on consumer complaint narratives using Python.   The objective is to understand recurring themes and patterns in complaints through text preprocessing and n-gram analysis.
## Business Context
Consumer complaint data is largely unstructured. This analysis focuses on cleaning and transforming free-text narratives into interpretable insights that can support downstream analytics such as complaint categorisation or topic modelling.

## What was done
- Handled missing complaint narratives
- Text normalisation (lowercasing, punctuation removal)
- Stopword removal using NLTK
- Tokenisation of complaint text
- Bigram (n-gram) frequency analysis
- Visualisation of the most frequent bigrams

## Tools & Libraries
- Python
- pandas
- NLTK
- matplotlib
- collections (Counter)

## Key Outcome
The analysis highlights frequently occurring word pairs related to credit reporting, payments, and dispute resolution, providing a structured view of dominant complaint themes.

## Notes
This notebook focuses on exploratory NLP techniques. It is intended as a foundation for further work such as TF-IDF, topic modelling, or supervised classification.
