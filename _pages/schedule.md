---
layout: page
permalink: /schedule/
title: schedule
description: 
nav: true
nav_order: 2
---



#### 15. September 2022
Topic: Deconstructing Ranking Abilities of Language Models (M.Sc. defense)

<details><summary>Abstract</summary>
Nowadays, information retrieval plays an important role in our daily lives. Whether we're
searching the web, shopping for products online, or trying to find our favorite movies on a
streaming platform: An information retrieval system will be responsible for tackling these
tasks. As a consequence of recent advances in natural language processing, employing
large pre-trained language models as part of a text retrieval pipeline has become a
common approach. However, despite their proven effectiveness, these neural network
based models are functional black boxes, meaning it is not clear to us as to how they
arrive at certain decisions. To get a better understanding of the inner workings of such
a model, we apply the recently emerging probing paradigm. By employing a diagnostic
classifier, this approach enables us to analyze how certain properties are encoded within
a model's hidden representations. Unlike previous research that has focused on general
linguistic properties, we explicitly study the layer-wise distribution of ranking related
knowledge throughout the popular BERT model, a large neural network that has been
trained on massive amounts of text data. In this thesis, we provide evidence that BERT
not only stores ranking related concepts, but also orders them in a hierarchical manner.
Moreover, we leverage our findings to design a multi-task learning setup which infuses
task specific information at different layers of BERT, in order to improve the model's
ability to rank.
</details>

Presenter: Fabian Beringer 

#### 04. August 2022
Another Gong-Show: 5-min short presentations of relevant papers/presentations from recent conferences.

#### 28. July 2022
ACL'22 Gong-Show: 5-min short presentations of relevant papers/presentations from ACL'22. If you would like to present a paper, please ping `idahl[at]l3s.de`.

#### 21. July 2022
SIGIR'22 Gong-Show: 5-min short presentations of peoples favorite papers/presentations from SIGIR'22. If you would like to present a paper, please ping `idahl[at]l3s.de`.

#### 14. July 2022
SIGIR & ICTIR break.

#### 07. July 2022
Nothing.

#### 30. June 2022

Topic: Supervised Contrastive Learning Approach for Contextual Ranking

<details><summary>Abstract</summary>
Contextual ranking models have delivered impressive performance improvements over classical models in the document ranking task. However, these highly over-parameterized models tend to be data-hungry and require large amounts of data even for fine tuning.This paper proposes a simple yet effective method to improve ranking performance on smaller datasets using supervised contrastive learning for the document ranking problem. We perform data augmentation by creating training data using parts of the relevant documents in the query-document pairs. We then use a supervised contrastive learning objective to learn an effective ranking model from the augmented dataset. Our experiments on subsets of the TREC-DL dataset show that, although data augmentation leads to an increasing the training data sizes, it does not necessarily improve the performance using existing pointwise or pairwise training objectives. However, our proposed supervised contrastive loss objective leads to performance improvements over the standard non-augmented setting showcasing the utility of data augmentation using contrastive losses. Finally, we show the real benefit of using supervised contrastive learning objectives by showing marked improvements in smaller ranking datasets relating to news (Robust04), finance (FiQA), and scientific fact checking (SciFact).
</details>

Presenter: Abhijit Anand
