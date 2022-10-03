# HackatonZakupki
## Task
build intelligent cluster for the analysis of procurement objects and their attributes using artificial intelligence
## Solution
- clear string columns
- lemmatization words
- build embeddings by TF-IDF on description columns
- use cosinus similarity with input description to find similar descritption in database
- sorted by value of cosinus similarity
- analyst recevied data for recomendation to provider
## Technology
- Pandas, numpy, seaborn, matplotlib, sklearn,
- lemmatization (pymystem3)
- build embeddings with TF-IDF (TfidfVectorizer from sklearn)
