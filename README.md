# Text Similarity Using Python

## What is Text Similarity? 

Text Similarity is the process of comparing a piece of text with another and finding the similarity between them. It’s basically about determining the degree of closeness of the text.

## How does text similarity work?

We must first change the input text into a more machine-readable form by turning it into embeddings. These embeddings are then transformed into vectors that the computer can understand in order to calculate the similarity. 

## Arxiv Dataset

For nearly 30 years, ArXiv has served the public and research communities by providing open access to scholarly articles from a wide range of disciplines. This rich corpus of information offers significant, but sometimes overwhelming depth.

## Word2Vec

A predictive technique for creating word embeddings is Word2Vec. Word2Vec is a pre-trained two-layer neural network, in contrast to other techniques that needed to be "trained" on the working corpus.

It uses the text corpus as input and produces a collection of feature vectors that represent the words in the corpus. One of two neural network-based techniques is utilized:
* Skip-Gram 
* Continuous Bag of Words (CBOW)

1. Continuous Bag Of Words

Takes the context of each word as the input and tries to predict the word corresponding to the context. Here, context simply means the surrounding words. 

2. Skip-Gram Model 

The Skip-gram model learns the vector representation of the target word as it predicts the words in the context. The context words are used to create representations.



