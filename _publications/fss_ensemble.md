---
title: "More than the Sum of Its Parts: Ensembling Backbone Networks for Few-Shot Segmentation"
collection: publications
category: manuscripts
permalink: /publication/fss_ensemble
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2024-01-01
venue: '2024 International Joint Conference on Neural Networks (IJCNN)'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://arxiv.org/pdf/2402.06581'
citation: 'Catalano, N., Maranelli, A., Chiatti, A., & Matteucci, M. (2024, June). More than the Sum of Its Parts: Ensembling Backbone Networks for Few-Shot Segmentation. In 2024 International Joint Conference on Neural Networks (IJCNN) (pp. 1-8). IEEE.
'
---

Semantic segmentation is a key prerequisite to
robust image understanding for applications in Artificial In-
telligence and Robotics. Few Shot Segmentation, in particular,
concerns the extension and optimization of traditional segmen-
tation methods in challenging conditions where limited training
examples are available. A predominant approach in Few Shot
Segmentation is to rely on a single backbone for visual feature
extraction. Choosing which backbone to leverage is a deciding
factor contributing to the overall performance. In this work, we
interrogate on whether fusing features from different backbones
can improve the ability of Few Shot Segmentation models to
capture richer visual features. To tackle this question, we propose
and compare two ensembling techniques—Independent Voting
and Feature Fusion. Among the available Few Shot Segmentation
methods, we implement the proposed ensembling techniques
on PANet. The module dedicated to predicting segmentation
masks from the backbone embeddings in PANet avoids trainable
parameters, creating a controlled ‘in vitro’ setting for isolating
the impact of different ensembling strategies. Leveraging the
complementary strengths of different backbones, our approach
outperforms the original single-backbone PANet across standard
benchmarks even in challenging one-shot learning scenarios.
Specifically, it achieved a performance improvement of +7.37%
on PASCAL-5i and of +10.68% on COCO-20i in the top-
performing scenario where three backbones are combined. These
results, together with the qualitative inspection of the predicted
subject masks, suggest that relying on multiple backbones in
PANet leads to a more comprehensive feature representation, thus
expediting the successful application of Few Shot Segmentation
methods in challenging, data-scarce environments