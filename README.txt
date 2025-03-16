Sentiment Analysis Project

 Overview
This project is a sentiment analysis tool that uses Natural Language Processing (NLP) techniques to analyze text input and determine whether the sentiment is positive, negative, or neutral. It also visualizes sentiment distribution using a pie chart.

 Features
- Text preprocessing including tokenization, stopword removal, and lemmatization.
- Sentiment analysis using NLTK's VADER SentimentIntensityAnalyzer.
- Optional custom sentiment lexicon support.
- Visualization of sentiment distribution via a pie chart.
- Interactive user interface using Gradio.


This will open a web-based interface where users can enter text to analyze sentiment.

 How It Works
1. The input text is cleaned by removing punctuation, tokenizing, removing stopwords, and lemmatizing.
2. Sentiment scores are generated using VADER SentimentIntensityAnalyzer.
3. The sentiment type is determined based on the scores.
4. A pie chart is generated to visualize the sentiment distribution.
5. Results are displayed in the Gradio interface.

 API Endpoint
The Gradio interface exposes an API that can be used programmatically. The API returns the sentiment label, sentiment scores, and a pie chart.

 Note:-
- If using a custom sentiment lexicon, ensure the `lexiconalsam.txt` file exists and follows the `word:score` format.
- The app can be shared using the `share=True` option in `iface.launch()`.


