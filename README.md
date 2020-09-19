# Interpritability
interpretability experiments
- V1: TF-IDF; with Gensim word2vec similarities
- V2: Keras Embedding Word2vec
- V3: GloVe Embedding Word2vec
  - V2 & V3 use embedding layer so explainer only use word IDs
- V4: GloVe Embedding Word2vec
  - use actual word vector values in explainer


## StackOverflow Data - 20200919
- [sof_interpretability_v0](https://github.com/DrJieTao/Interpritability/blob/master/sof_interpretability_v0.ipynb): using GloVe embedding as weights
- [sof_interpretability_v1](https://github.com/DrJieTao/Interpritability/blob/master/sof_interpretability_v1.ipynb): penetration of embedding models
