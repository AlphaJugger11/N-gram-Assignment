# N-Gram Language Models

This repository contains an implementation of **N-Gram Language Models**, including Unigram, Bigram, Trigram, and Bidirectional Models. Additionally, it incorporates smoothing techniques such as **Kneser-Ney Smoothing** to improve probability estimations.

## Features
- Unigram, Bigram, Trigram, and Bidirectional Models
- Text Preprocessing for corpus cleaning
- Smoothing Methods (e.g., Kneser-Ney Smoothing)
- Diary Generation using trained models

## Installation
Ensure you have Python installed along with the required dependencies:

```sh
pip install nltk numpy pandas
.
├── N_grams.ipynb      # Main Jupyter Notebook
├── dataset/           # Folder containing raw text files for training
└── cleaned_dataset/   # Folder where preprocessed text files are stored
