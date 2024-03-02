---
title: 'SetCSE: Set Operations using Contrastive Learning of Sentence Embeddings'
date: 2023-02-27
permalink: /blogs/setcse/
tags:
  - Natural Language Processing
  - Contrastive Learning
  - Sentence Embedding
  - Deep Learning
---

Taking inspiration from Set Theory, we introduce SetCSE, an innovative information retrieval framework. SetCSE employs sets to represent complex semantics and incorporates well-defined operations for structured information querying within the provided context. In alignment with this framework, we introduce an inter-set contrastive learning objective to enhance language model comprehension concerning the given semantics. Additionally, we present a suite of operations that leverage the enhanced sentence embeddings for querying, including SetCSE intersection, difference, and operation series. Throughout this paper, we demonstrate that SetCSE adheres to the conventions of natural language expression, provides a significant enhancement in the discriminatory capability of underlying language models, and enables numerous information retrieval tasks involving complex and intricate prompts that cannot be achieved using existing search methods.

$ $
$ $

SetCSE Framework Illustration
======
![](/mysite/images/setcse/flowchart.png)

$ $

Evaluation
======

t-SNE plot of sentence embeddings from models with and without SetCSE
------
![](/mysite/images/setcse/batch2_AGT.png)

$ $

Application
======

![](/mysite/images/setcse/ESG.png)

![](/mysite/images/setcse/Active_Learning.png)