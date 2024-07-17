---
title: "Cross-modality debiasing: using language to mitigate sub-population shifts in imaging"
collection: publications
permalink: /publication/paper-3
excerpt: 'Authors: Cross-modality debiasing: using language to mitigate sub-population shifts in imaging'
date: 2024-01-01
venue: 'arXiv 2024'
slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2403.07888'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Sub-population shift is a specific type of domain shift that highlights changes in data distribution within specific sub-groups or populations between training and testing. Sub-population shift accounts for a significant source of algorithmic bias and calls for distributional robustness. Recent studies found inherent distributional robustness in multi-modality foundation models, such as the vision-language model CLIP, yet this robustness is vulnerable through parameter fine-tuning. In this paper, we propose leveraging the connection of robustness among different modalities and reshaping the distributional robustness of one modality with another. Specifically, in the context of the distributional robustness of CLIP, we propose to leverage natural language inputs to debias the image feature representations, to improve worst-case performance on sub-populations. Our extensive empirical studies show that image representations debiased by natural language can achieve significant performance improvement and reduction of performance instability under sub-population shifts.