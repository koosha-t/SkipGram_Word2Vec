# Word Embedding: Building a Skip Gram Word2Vec Model

In this repository, I'm going to build a Word2Vec word-embedding model on Amazon reviews. 

### Why Building a Word2Vec from Scratch?
In some cases, the corpus of documents under the study might be significantly different than the corpus that the existing word2vec models are trained on. For instance, Google word2vec is trained on millions of official text books. We might not be able to re-use and fine-tune that model to perform word embedding on call centre conversations, where there might be many informal keywords along with the words that are use in specific contexts only.
