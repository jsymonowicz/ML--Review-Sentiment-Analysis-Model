### Sentiment Analysis and Text Preprocessing

This repository contains Python scripts for performing sentiment analysis and exploring text preprocessing techniques on product reviews. Here's a brief overview of the files:

- **sentiment_analysis.py**: This script conducts sentiment analysis on a dataset of product reviews and also performs similarity analysis.
  
- **testing_exception_stop_words.py**: This script evaluates the impact of removing stop words, punctuation, and spaces on the polarity score of a review. The goal is to determine the most suitable text preprocessing methods for preserving the true sentiment.
  
- **testing_exception_stop_words.py**: Another script dedicated to testing which stop words should not be removed from the `predict_sentiment` function to maintain the accuracy of sentiment analysis.

### Setup

Before running the scripts, ensure the following installations are performed in your command prompt:

```
python -m spacy download en_core_web_sm
pip install spacytextblob
python -m textblob.download_corpora
```

### Additional Resources

Please refer to **sentiment_analysis_report.pdf** for detailed information on the dataset used, preprocessing steps, evaluation of results, and insights into the strengths and limitations of the model.

Feel free to explore the scripts and report for more insights into sentiment analysis and text preprocessing techniques!
