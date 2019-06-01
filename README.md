# Movie review classification

In this project we classify movie reviews according to the rank that a user gave to the movie. The model is then able to classify how positive/negative the user considered the movie by looking at the review they did.

![](images/cc.gif)

## Task

Based on a movie review assign it to 1,2,..., 10 according to the grade that the person gave to the movie. It can be seen as a variation of sentiment analysis. The current state of the art average accuracy for this model ≃ 49%.

## Dataset

[IMDb dataset](https://www.imdb.com/interfaces/)

## What is used?

A PyTorch implementation of [Hierarchical Attention](https://www.cs.cmu.edu/~./hovy/papers/16HLT-hierarchical-attention-networks.pdf) for document classification is coded and used.

![](images/hiererchical_attention.png)

