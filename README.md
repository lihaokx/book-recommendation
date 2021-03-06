# Content-Based-Recommendation system

## Required modules:
 pandas, numpy, nltk, sklearn, matplotlib, gensim 

## Codes could be seperated as following parts.

### 1. Text Preprocessing
Remove ASCII characters, converting lower case, removing stop words, html and punctuation from description.

### 2. Building Average [Word2Vec](https://en.wikipedia.org/wiki/Word2vec) Model

 - Use Google pretrained Word2Vec Model. 
 - Generate the average word2vec for the each book description.
 - Calculate cosine similarities between the selected book and the whole dataset.
 - Sort cosine similarities and recommend the top 5 books.

### 3. Building [TF-IDF](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) + Word2Vec Model

 - Building TFIDF model and calculate TFIDF score.
 - Transform data into TF-IDF+Word2Vec.
 - Calculate cosine similarities between the selected book and the whole dataset.
 - Sort [cosine similarities](https://en.wikipedia.org/wiki/Cosine_similarity) and recommend the top 5 books.

## Conclusion:
 The resutls show TF-IDF+Word2Vec model has a better similarities scores compared with other models.
 
 ![Result](./result.png)



