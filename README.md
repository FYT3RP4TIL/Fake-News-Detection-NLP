# Fake News Detection

## Overview  
The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable.  Our project aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles.

![Screenshot 2023-09-27 022804](https://github.com/Sudhanshu21xx/Fake-News-Detection-NLP/assets/113416452/6c940d88-d823-456a-b666-dc61e331aef3)


## Dataset Description

* True.csv: True collected news from various articles, sources.
* Fake.csv: Fake collected news from various articles, sources.
  
![Screenshot 2023-09-27 022942](https://github.com/Sudhanshu21xx/Fake-News-Detection-NLP/assets/113416452/98913d1f-8e61-4dd9-ae13-6d83ba92f34f)

## Try It Out

1. Clone the repo to your local machine-  
`> https://github.com/Sudhanshu21xx/Fake-News-Detection-NLP.git`  
`> cd Fake-news-Detection`

2. Make sure you have all the dependencies installed-  
 * python 3.6+
 * numpy
 * tensorflow
 * pandas
 * sklearn
 * nltk
   * For nltk, run these commands in your notebook --  
       * `>>> import nltk`
       * `>>> nltk.download()`}

## Methodologies Used

 * [Tokenization](https://www.geeksforgeeks.org/nlp-how-tokenizing-text-sentence-words-works/)
 * [Stemming](https://www.geeksforgeeks.org/introduction-to-stemming/)
 * [Stopword Removal](https://www.geeksforgeeks.org/removing-stop-words-nltk-python/)
 * [Splitting Data](https://www.geeksforgeeks.org/how-to-split-a-dataset-into-train-and-test-sets-using-python/)
 * [Vectorization](https://www.geeksforgeeks.org/feature-extraction-techniques-nlp/)

## Model Used 

 * [Logestic Regression](https://www.geeksforgeeks.org/understanding-logistic-regression/)
 * [Passive Agressive Classifier](https://www.geeksforgeeks.org/passive-aggressive-classifiers/)
    
