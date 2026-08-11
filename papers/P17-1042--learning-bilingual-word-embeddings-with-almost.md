---
id: P17-1042
title: Learning bilingual word embeddings with (almost) no bilingual data
authors: Mikel Artetxe; Gorka Labaka; Eneko Agirre
year: 2017
venue: ACL 2017
read: 2025-08-31
tags: cross-lingual alignment, bilingual lexicon induction
cited: 490
archaic: true
---

<!-- Imported verbatim from paper_summaries.html on the website, written before this app existed. Unedited. -->

Using previous methods that learn a linear transformation, considers a bootstrapping method using a very small dictionary and iteratively improving it by retraining and regenerating a word-word dictionary by choosing nearest neighbor of transformed vectors. The learned transformation tends to be the same regardless of starting dictionary, and observed errors are very similar to that of Artetxe et al. (2016).

- Bootstrapping from a very small (~25 word pairs) dictionary performs as well as using a large dictionary.

- Using very small starting dictionary leads to similar final dictionary as Artetxe et al. (2016) indicates that learning a transformation in an unsupervised manner could be possible.

- However, (while not mentoned in the paper) performance does correlate with the similarity between the two languages.

## Thoughts

- This likely does not work on two very different languages, because the text embeddings learned in the languages likely take a very different structure.

- At each time step, are we using all words as anchors or only the most "confident" words?
