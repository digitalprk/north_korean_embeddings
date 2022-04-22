Pre-trained word vectors for the North Korean language
=====

* Trained on a 200 million word corpus of North Korean text: news articles, magazines, literature and political essays.
* Vocabulary size: 64979


Download:
=====
https://datank2.s3.ap-southeast-1.amazonaws.com/nk200sg7.bin


Usage:
======

```
import gensim.models.keyedvectors as word2vec
model = word2vec.KeyedVectors.load_word2vec_format('nk200sg7.bin', binary=False)
```
