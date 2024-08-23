---
title: "Logic Unveils Truth, While Disguise Obscures It: Transition Logic Augmented Response Selection for Multi-Turn Dialogue"
collection: publications
category: conferences
permalink: /publication/2023-emnlp-logic
date: 2023-12-06
venue: 'Findings of EMNLP'
location: Singapore
author: Tingchen Fu,Xueliang Zhao,Lemao Liu,Rui Yan
cofirst: 2
url: 'https://aclanthology.org/2023.findings-emnlp.513.pdf'
---

Multi-turn response selection aims to retrieve a response for a dialogue context from a candidate pool and negative sampling is the key to its retrieval performance. However, previous methods of negative samples tend to yield false negatives due to the one-to-many property in open-domain dialogue, which is detrimental to the optimization process. To deal with the problem, we propose a sequential variational ladder auto-encoder to capture the diverse one-to-many transition pattern of multiple characteristics in open-domain dialogue. The learned transition logic thus assists in identifying potential positives in disguise. Meanwhile, we propose a TRIGGER framework to adjust negative sampling in the training process such that the scope of false negatives dynamically updates according to the model capacity. Extensive experiments on two benchmarks verify the effectiveness of our approach.
