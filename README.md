# smartcities100
This repo contains a feature extraction from Twitter content (NLP and Sentiment Analysis) of the 109 most advanced Smart-Cities worldwide. (cf. Smart City Index 2020 by IMD Business School https://www.imd.org/smart-city-observatory/smart-city-index/#:~:text=Singapore%2C%20Helsinki%20and%20Zurich%20have,%E2%80%9Csmart%E2%80%9D%20their%20cities%20are) 

Features extracted from this dataset assume to be representative of the whole population of existing Smart-Cities nowadays. It will be used as a comparison point to train predictive models and test probabilistic hypothesis on samples.  

In this repo you can find:
- Feature Extraction 1 for each Smart-City (including weight of smart-city BoWs https://github.com/DemocracyStudio/smartcityBoWs)
- Feature Extraction 2 for each Smart-City
- the raw .csv file of twitter content

FEATURE EXTRACTION 1 :

Tweet-level features : 
    - delete null rows
    - tweet length / num of words for each tweet / number of sentences / average length of words
    - vader sentiment (neg/neu/pos/compound)

City-level features :
    - num of tweets
    - avg tweet length / avg num words per tweet/ average number of sentences / average word length / average sentiment scores (neg/neu/pos/compound) 
    - num of words into concatenated tweets
    - weight of thematic BoW
    - extract features from counts of stopwords, ponctuation ... https://towardsdatascience.com/beginners-guide-for-data-cleaning-and-feature-extraction-in-nlp-756f311d8083
    - convert emoji, emoticons into words
    - nlp tasks (expand contractions, remove digits, @mentions, url, punctuation, tokenizing, cleaning stopwords, useless, lemmatize, num clean tokens, extract most frequent 100...) 
    - sentiment analysis vader

FEATURE EXTRACTION 2 :

