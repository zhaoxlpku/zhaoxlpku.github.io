---
title: "Learning an Effective Context-Response Matching Model with Self-Supervised Tasks for Retrieval-based Dialogues"
collection: publications
category: conferences
permalink: /publication/2020-aaai-learning
date: 2021-02-02
venue: 'AAAI'
location: Online
author: Ruijian Xu,Chongyang Tao,Daxin Jiang,Xueliang Zhao,Dongyan Zhao,Rui Yan
cofirst: 0
url: 'https://arxiv.org/abs/2009.06265'
---

Building an intelligent dialogue system with the ability to select a proper response according to a multi-turn context is a great challenging task. Existing studies focus on building a context-response matching model with various neural architectures or PLMs and typically learning with a single response prediction task. These approaches overlook many potential training signals contained in dialogue data, which might be beneficial for context understanding and produce better features for response prediction. Besides, the response retrieved from existing dialogue systems supervised by the conventional way still faces some critical challenges, including incoherence and inconsistency. To address these issues, in this paper, we propose learning a context-response matching model with auxiliary self-supervised tasks designed for the dialogue data based on pre-trained language models. Specifically, we introduce four self-supervised tasks including next session prediction, utterance restoration, incoherence detection and consistency discrimination, and jointly train the PLM-based response selection model with these auxiliary tasks in a multi-task manner. By this means, the auxiliary tasks can guide the learning of the matching model to achieve a better local optimum and select a more proper response. Experiment results on two benchmarks indicate that the proposed auxiliary self-supervised tasks bring significant improvement for multi-turn response selection in retrieval-based dialogues, and our model achieves new state-of-the-art results on both datasets.