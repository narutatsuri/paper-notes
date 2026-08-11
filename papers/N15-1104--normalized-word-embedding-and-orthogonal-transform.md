---
id: N15-1104
title: Normalized Word Embedding and Orthogonal Transform for Bilingual Word Translation
authors: Xing Chao; Dong Wang; Chao Liu; Yiye Lin
year: 2015
venue: NAACL 2015
read: 2025-08-31
tags: Cross-lingual alignment, linear transformation, orthogonal transformation
cited: 419
archaic: true
---

<!-- Imported verbatim from paper_summaries.html on the website, written before this app existed. Unedited. -->

Uses static word embeddings (word2vec-style). Claims Mikolov et al. (2013)'s approach is ill-posed because the same similarity metrics are not used during training and testing. Proposes to length-normalize vectors during training.

- First paper to propose the orthogonal transform approach within projection-based methods for cross-lingual alignment.

- Approach for learning linear projection between embeddings of different dimensions is ad-hoc.

- Linear projection is learned using data from Google Translate.

## Thoughts

- Wonder if unsupervised learning of the projection is possible.
