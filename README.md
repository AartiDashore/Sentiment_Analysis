# Sentiment_Analysis
A python based program to understand the sentiment of a statement using TextBlob python library (Jupyter).

## Sentiment Analysis using TextBlob
This is a Python code repository that implements sentiment analysis on a given text dataset using the TextBlob library. The code uses Natural Language Processing (NLP) techniques to analyze the sentiment of the text data and classify them as either positive, negative or neutral.

## Getting Started
### Prerequisites
The code requires the TextBlob library to be installed. You can install it using the following command:
```
pip install textblob
```

### Usage
1. Clone the repository.
2. Install the TextBlob library using pip install textblob.
3. Add your dataset in CSV format to the repository.
4. Open the Jupyter notebook `sentiment_analysis.ipynb in Jupyter Notebook or JupyterLab.
5. Run the cells in the notebook to analyze the sentiment of the text data.

The sentiment_analysis.ipynb notebook contains the following sections:

### Importing the required libraries.
1. Reading the dataset into a pandas dataframe.
2. Preprocessing the text data by removing stop words, punctuations, and converting the text to lowercase.
3. Performing sentiment analysis using TextBlob and adding the sentiment polarity scores to the dataframe.
4. Classifying the sentiment of each text as positive, negative or neutral based on the polarity scores.
5. Visualizing the distribution of the sentiment classifications using a bar chart.

The notebook also includes comments and explanations for each step in the code.

### Customization
You can customize the code to suit your needs. For example, you can modify the preprocessing steps to include additional text cleaning techniques, or you can change the sentiment classification thresholds to classify the sentiments differently.

## Conclusion
This code repository provides a simple and easy-to-understand implementation of sentiment analysis using the TextBlob library. It can be used as a starting point for more advanced sentiment analysis tasks or as a reference for understanding how sentiment analysis works.
