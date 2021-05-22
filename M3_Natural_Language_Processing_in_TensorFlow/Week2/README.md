# Word Embeddings
## Introduction
Last week you saw how to use the Tokenizer to prepare your text to be used by a neural network by converting words into numeric tokens, and sequencing sentences from these tokens. This week you'll learn about Embeddings, where these tokens are mapped as vectors in a high dimension space. With Embeddings and labelled examples, these vectors can then be tuned so that words with similar meaning will have a similar direction in the vector space. This will begin the process of training a neural network to udnerstand sentiment in text -- and you'll begin by looking at movie reviews, training a neural network on texts that are labelled 'positive' or 'negative' and determining which words in a sentence drive those meanings.

## [Google Colab](https://colab.research.google.com)
* [Colab FAQs](https://research.google.com/colaboratory/faq.html)

## Readings
### IMDB reviews dataset
Please find the link to he IMDB reviews dataset [here](http://ai.stanford.edu/~amaas/data/sentiment/).\
You will find here 50,000 movie reviews which are classified as positive of negative.\

### TensorFlow datasets
Please find [here](https://github.com/tensorflow/datasets/tree/master/docs/catalog) the datasets GitHub url.\
For more information, please checkout the [TensorFlow datasets documentation](https://www.tensorflow.org/datasets/catalog/overview).

[https://github.com/tensorflow/datasets/tree/master/docs/catalog](https://github.com/tensorflow/datasets/tree/master/docs/catalog)
