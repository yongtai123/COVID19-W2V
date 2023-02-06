# COVID19-W2V

Usage:
```
from gensim.models import KeyedVectors
rural_wv = KeyedVectors.load('model/rural/word2vec.wordvectors')
rural_wv.similarity('#covid19', '#vaccine')
```
