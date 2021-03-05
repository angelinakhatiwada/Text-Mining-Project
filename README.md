# Text Mining Project

*Angelina Khatiwada, MSc Data Science and Economics, UNIMI*

Feb, 2021

#### Datasets:
- Coprus 1: [The SMS Spam Collection v.1](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/), a public set of SMS labeled messages that have been collected for mobile phone spam research and tagged according being legitimate (ham) or spam

- Corpus 2: 20 [BBC News Articles](v) (collected through web scraping in Part b)

### Project description: 

#### Part a:  Text data pre-processing
- Importing text data
- Corpus cleaning (removing stopwords, punctuation)
- Tokenization (working with unigrams, bigrams, unigrams and bigrams)
- Word frequency visualization using WordCloud
- Vectorization and Feature extraction (CountVectorizer, TfidfVectorizer)
- PCA, Feature selection (TruncatedSVD, chi2)
- Standartization 
- Creating pipelines for data processing

#### Part b: Classication and clustering, topic model and summarisation

*Spam/Non spam emails*:
- Preprocessing using pipelines
- Classification:
  - splitting data into training and test
  - tuning parameteres with GridSearchCV
  - models applied: Logistic Regression, Naive Bayes Classifier, Support Vector Machine, Perceptron
  - model evaluation
  - plotting ROC curve
  - classifying new emails
- Clustering using K-means and Agglomerative Clustering

*BBC News Articles*:
- Text web scraping
- Text preprocessing using pipelines
- Topic modelling with Latent Dirichlet Allocation (LDA) and topics visualization
- Summarization with embeddings and TextRank 

**Libraries used:** nltk, scikit-learn, gensim, matplotlib, beautifulsoup4, scipy, NetworkX, pandas, numpy, wordcloud
