
---
title: Se3
subtitle: Semantic Self-Segmentation for Abstractive Summarization of Long Documents in Low-Resource Regimes
description: Se3
layout: service
authors: Gianluca Moro, Lorenzo Valgimigli
serverlink: http://137.204.107.42:37338/
---



The quadratic memory complexity of transformers prevents long document summarization in low computational resource scenarios. State-of-the-art models need to apply input truncation, thus discarding and ignoring potential summary-relevant contents, leading to a performance drop. Furthermore, such loss is generally destructive for semantic text analytics in high-impact social domains such as the legal ones. In this paper, we propose a novel semantic self-segmentation (Se3) approach for long document summarization to address the critical problems of low-resource regimes, namely to process longer inputs than the GPU memory capacity and produce accurate summaries despite the availability of only a few dozens of training instances. Se3 segments a long input into semantically coherent chunks, allowing transformers to summarize very long documents without truncation by summarizing each chunk and concatenating the results. Experimental outcomes show that our approach significantly improves the performance of abstractive summarization transformers, even with just a dozen of labeled data, achieving new state-of-the-art results on two legal datasets of different domain and content. Finally, we perform ablation studies to assess how the different components of our method contribute to the performance gain.

Keywords: NLP; long document summarization; transformers; legal analytics. 

