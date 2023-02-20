# COVID19-W2V

This repository contains urban and rural word-embedding models from the [paper](https://www.jmir.org/2023/1/e42985) Examining Rural and Urban Sentiment Difference in COVID-19–Related Topics on Twitter: Word Embedding–Based Retrospective Study.

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

If you find our model or paper useful, please consider citing:

```
@article{liu2023examining,
  title={Examining Rural and Urban Sentiment Difference in COVID-19--Related Topics on Twitter: Word Embedding--Based Retrospective Study},
  author={Liu, Yongtai and Yin, Zhijun and Ni, Congning and Yan, Chao and Wan, Zhiyu and Malin, Bradley},
  journal={Journal of Medical Internet Research},
  volume={25},
  pages={e42985},
  year={2023},
  publisher={JMIR Publications Toronto, Canada}
}
```
