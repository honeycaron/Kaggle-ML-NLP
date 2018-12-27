# Kaggle-ML-NLP
Natural Language Processing(NLP) implementation on various competitions in [Kaggle](https://www.kaggle.com)

## Detail
### 1. Bag of Words Meets Bags of Popcorn
#### (1) Bag of Words
- Practice Skills
  - Data Cleaning and Text Preprocessing (Module: BeautifulSoup, re, nltk)
  - Bag of Words (Module: scikit-learn's CountVectorizer)
  - Supervised Learning (Module: Random Forest)
  
#### (2) Word Vectors
- Practice Skills
  - Data Cleaning and Text Preprocessing (Module: BeautifulSoup, re, nltk)
  - Distributed word vectors (Module: word2vec/gensim, cython)
  - Training algorithm: Hierarchical softmax (default)
  - Word vector dimensionality: 300
  - Minimum word count: 40
  - Vector Averaging
  - Clustering (Module: sklearn.cluster's KMeans)

## Result
Bag of Words has shown a slightly better performance. The biggest reason is, in case of this competition, averaging the vectors and using the centroids lose the order of words, making it very similar to the concept of Bag of Words. The fact that the performance is similar (within range of standard error) makes all three methods practically equivalent. 


## Images
Apparently, kitchen is odd...<br><br>
<img src="Bag of Words Meets Bags of Popcorn/word_vectors_output1.PNG" alt="result" width="1000">
<br><br><br>And Queen is similar to Princess! and awful is terrible!<br><br>
<img src="Bag of Words Meets Bags of Popcorn/word_vectors_output2.PNG" alt="result" width="1000">
<br><br><br>This is how each cluster looks like.. Some are really similar to each other and some are...?<br><br>
<img src="Bag of Words Meets Bags of Popcorn/word_vectors_Clustering_output1.PNG" alt="result" width="1000">

## References
**Bags of Popcorn**
1. Bag of Words Meets Bags of Popcorn [Tutorial](https://www.kaggle.com/c/word2vec-nlp-tutorial#description)
