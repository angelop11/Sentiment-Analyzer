# Sentiment Analysis with NLTK

This Python project performs sentiment analysis on a given text and visualizes the emotional content with a bar chart. It uses the NLTK library for text processing, including tokenization, stop word removal, lemmatization, and sentiment analysis. The project also uses `matplotlib` for data visualization.

## Features
- Tokenizes input text into words.
- Removes stop words to focus on meaningful words.
- Lemmatizes words (e.g., converts plural forms to singular, or the base form of a word).
- Matches words with associated emotions from a predefined list.
- Analyzes the overall sentiment of the text using NLTK's VADER sentiment analysis.
- Visualizes the frequency of emotions found in the text as a bar chart.

## Requirements
To run this project, you need to install the following Python libraries:
- `nltk`
- `matplotlib`

You can install them via `pip3`:

```bash
pip3 install nltk matplotlib

![Emotion Frequency](https://github.com/angelop11/Sentiment-Analyzer/blob/main/graph.png)

