---
title: "Exploring ways to incorporate additional knowledge to improve Natural Language Commonsense Question Answering"
collection: publications
permalink: /publication/2019-9-10-paper-title-number-2
excerpt: 'In this paper we evaluate multiple ways to incorporate knowledge in large Neural Language Models.'
date: 2019-9-10
venue: 'arxiv.org'
paperurl: 'https://arxiv.org/abs/1909.08855'
citation: 'Mitra, A., Banerjee, P., Pal, K. K., Mishra S. & Baral, C. (2019, July). Exploring ways to incorporate additional knowledge to improve Natural Language Commonsense Question Answering. CoRR, arxiv.org'
---
DARPA and Allen AI have proposed a collection of datasets to encourage research in Question Answering domains where (commonsense) knowledge is expected to play an important role. Recent language models such as BERT and GPT that have been pre-trained on Wikipedia articles and books, have shown decent performance with little fine-tuning on several such Multiple Choice Question-Answering (MCQ) datasets. Our goal in this work is to develop methods to incorporate additional (commonsense) knowledge into language model based approaches for better question answering in such domains. In this work we first identify external knowledge sources, and show that the performance further improves when a set of facts retrieved through IR is prepended to each MCQ question during both training and test phase. We then explore if the performance can be further improved by providing task specific knowledge in different manners or by employing different strategies for using the available knowledge. We present three different modes of passing knowledge and five different models of using knowledge including the standard BERT MCQ model. We also propose a novel architecture to deal with situations where information to answer the MCQ question is scattered over multiple knowledge sentences. We take 200 predictions from each of our best models and analyze how often the given knowledge is useful, how many times the given knowledge is useful but system failed to use it and some other metrices to see the scope of further improvements.

[Download paper here](https://arxiv.org/abs/1909.08855)

Recommended citation: Mitra, A., Banerjee, P., Pal, K. K., Mishra S. & Baral, C. (2019, July). Exploring ways to incorporate additional knowledge to improve Natural Language Commonsense Question Answering. CoRR, arxiv.org