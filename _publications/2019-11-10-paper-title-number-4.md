---
title: "Knowledge Guided Named Entity Recognition"
collection: publications
permalink: /publication/2019-11-10-paper-title-number-4
excerpt: 'In this paper I explore ways te regenerate explanations given a question and correct answer.'
date: 2019-11-10
venue: ''arxiv.org'
paperurl: 
citation: 'Pratyay Banerjee and Kuntal Kumar Pal and Murthy Devarakonda and Chitta Baral (2019, November). Knowledge Guided Named Entity Recognition. arxiv, CoRR.'
---

In this work, we try to perform Named Entity Recognition (NER) with external knowledge. We formulate the NER task as a multi-answer question answering (MAQA) task and provide different knowledge contexts, such as entity types, questions, definitions, and definitions with examples. Moreover, the formulation of the task as a MAQA task helps to reduce other errors. This formulation (a) enables systems to jointly learn from varied NER datasets, enabling systems to learn more NER specific features, (b) can use knowledge-text attention to identify words having higher similarity to 'entity type' mentioned in the knowledge, improving performance, (c) reduces confusion in systems by reducing the classes to be predicted, limited to only three (B, I, O), (d) Makes detection of Nested Entities easier. We perform extensive experiments of this Knowledge Guided NER (KGNER) formulation on 15 Biomedical NER datasets, and through these experiments, we see external knowledge helps. We will release the code for dataset conversion and our trained models for replicating experiments. 

[Download paper here](https://arxiv.org/abs/1911.03869)

Recommended citation: Pratyay Banerjee and Kuntal Kumar Pal and Murthy Devarakonda and Chitta Baral (2019, November). Knowledge Guided Named Entity Recognition. arxiv, CoRR.