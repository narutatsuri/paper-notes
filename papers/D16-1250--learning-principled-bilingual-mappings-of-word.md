---
id: D16-1250
title: Learning principled bilingual mappings of word embeddings while preserving monolingual invariance
authors: Mikel Artetxe; Gorka Labaka; Eneko Agirre
year: 2016
venue: EMNLP 2016
read: 2025-08-31
tags: cross-lingual alignment, linear transformation, orthogonal transformation
cited: 396
archaic: true
---

<!-- Imported verbatim from paper_summaries.html on the website, written before this app existed. Unedited. -->

Direct follow-up to Xing et al. (2015). Combines the optimization objectives of Xing et al. (2015) and Faruqui and Dyer (2014). Evaluates word embeddings and the learned transformation on translational similarity (How close the mapped vector from language $A$ is to the word in language $B$ with "same" meaning.) and word embeddings only on analogy solving task.

- Length-normalization is not important over orthogonal matrix.

- Adds mean centering constraint to optimization and states the optimization is equivalent to Faruqui and Dyer (2014) but does not alter monolingual embeddings manually.
