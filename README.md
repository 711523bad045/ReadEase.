# ReadEase.Project Description:
ReadEase is a Python-powered tool designed to analyze the readability and complexity of English sentences. It works by matching each word in a sentence with a pre-defined dataset (WordDifficulty.csv) that includes average reading times (I_Mean_RT). By averaging the scores of recognized words, ReadEase estimates the overall reading difficulty of a sentence.

This project is ideal for:

Educators evaluating student material

Language learners measuring sentence difficulty

Developers building readability features

Content creators aiming to write clearer text

Core Features:
Converts input text to lowercase and removes punctuation for accurate word matching.

Maps each word to its reading time complexity (if available).

Calculates an average sentence complexity score.

Provides a detailed per-word score breakdown, marking words not found in the dataset.
