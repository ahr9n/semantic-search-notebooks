# Jupyter Notebooks of Semantic Search

Thanks to [Google Colaboratory Notebooks](https://colab.research.google.com/), we almost did all our work and development on it.

## Quranic Semantic Search (AraVec + KSUCCA + FastText)

We explained everything (with examples) for all stages of the sentence embedding model, starting from installing requirements and pre-processing, ending with evaluation.

## Transformers Sentence Similarity

A Siamese network model, trained for zero-shot and few-shot text classification. The base model is xlm-roberta-base. It was trained on SNLI, MNLI, ANLI and XNLI.

It is a sentence-transformers model that maps sentences & paragraphs to a 768-dimensional dense vector space.

### Usage

After installing requirements, we used it on a query text to compare the transformer's results with our sentence embedding model results. For the transformer, it took about 13 mins to load and get the answers, however, the answers were not as good as ours.

### Give a try!
Open the notebook that you want to work with. Change the url domain from `github.com` to `githubtocolab.com`. The notebook will open in Google Colab, and you can run online every cell respectively.

## :hatching\_chick: Contributors
<table>
  <tr>
    <td align="center"><a href="https://github.com/OmarShamkh"><img src="https://avatars.githubusercontent.com/u/44472968?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Omar Shamkh</b></sub></a><br /><a href="https://github.com/ahr9n/quranic-search-v2/commits?author=OmarShamkh">💻</a></td>
    <td align="center"><a href="https://github.com/ahr9n"><img src="https://avatars.githubusercontent.com/u/52632898?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ahmad Abdulrahman</b></sub></a><br /><a href="https://github.com/ahr9n/quranic-search-v2/commits?author=ahr9n">💻</a></td>
  </tr>
</table>
