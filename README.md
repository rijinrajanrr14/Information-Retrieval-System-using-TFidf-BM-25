# Information-Retrieval-System-using-TFidf-BM-25
Building a information retrieval system using tf-idf and Okapi BM25, implementing it on fifa website

## TF-IDF
TF-IDF stands for “Term Frequency — Inverse Document Frequency”. This is a technique to quantify words in a set of documents. We generally compute a score for each word to signify its importance in the document and corpus. This method is a widely used technique in Information Retrieval and Text Mining.By vectorizing the documents we can further perform multiple tasks such as finding the relevant documents, ranking, clustering, etc. This exact technique was previously used when to perform a google search. 


TF-IDF = Term Frequency (TF) * Inverse Document Frequency (IDF)


## OKAPI-BM25
BM25 is a simple Python package and can be used to index the data, tweets in our case, based on the search query. It works on the concept of TF/IDF i.e. TF or Term Frequency — Simply put, indicates the number of occurrences of the search term in our tweet.
The BM25 algorithm aggregates and uses information from all the documents in the input data via the term frequency (TF) and inverse document frequency (IDF) based options.
