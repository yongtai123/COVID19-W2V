# COVID19-W2V

This repository contains urban and rural word-embedding models from the paper: Examining Rural and Urban Sentiment Difference in COVID-19 Related Topics on Twitter: A Word-Embedding based Infodemiology Study.

### Requirement:
```
gensim >= 4.1.2
```

### Usage:
```
from gensim.models import KeyedVectors
rural_wv = KeyedVectors.load('model/rural/word2vec.wordvectors')
rural_wv.similarity('#covid19', '#vaccine')
```

If you find our model or paper useful, please consider citing


