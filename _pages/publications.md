---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

* **Distributed Harmonization: Federated Clustered Batch Effect Adjustment and Generalization** <br>
  <b><u>Bao Hoang</u></b>, Yijiang Pang, Siqi Liang, Liang Zhan, Paul Thompson, Jiayu Zhou. <br>
  [KDD 2024] (Oral Presentation) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://dl.acm.org/doi/pdf/10.1145/3637528.3671590" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/illidanlab/distributed-cluster-harmonization" role="button" target="_blank"> Code </a> |
        <a href="../files/KDD2024Slide.pdf" role="button" target="_blank"> Slides </a>

    </summary>
   Independent and identically distributed (i.i.d.) data is essential to many data analysis and modeling techniques. In the medical domain, collecting data from multiple sites or institutions is a common strategy that guarantees sufficient clinical diversity, determined by the decentralized nature of medical data. However, data from various sites are easily biased by the local environment or facilities, thereby violating the i.i.d. rule. A common strategy is to harmonize the site bias while retaining important biological information. The ComBat is among the most popular harmonization approaches and has recently been extended to handle distributed sites. However, when faced with situations involving newly joined sites in training or evaluating data from unknown/unseen sites, ComBat lacks compatibility and requires retraining with data from all the sites. The retraining leads to significant computational and logistic overhead that is usually prohibitive. In this work, we develop a novel Cluster ComBat harmonization algorithm, which leverages cluster patterns of the data in different sites and greatly advances the usability of ComBat harmonization. We use extensive simulation and real medical imaging data from ADNI to demonstrate the superiority of the proposed approach.
  </details>  

* **Translingual Language Markers for Cognitive Assessment from Spontaneous Speech** <br>
  <b><u>Bao Hoang</u></b>, Yijiang Pang, Hiroko Dodge, Jiayu Zhou. <br>
  [InterSpeech 2024] <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://www.isca-archive.org/interspeech_2024/hoang24_interspeech.pdf" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/illidanlab/translingual-language-markers" role="button" target="_blank"> Code </a>
    </summary>
   Mild Cognitive Impairment (MCI) is considered a prodromal stage of dementia, including Alzheimer's disease, showing behavior changes and decreased executive function. In the InterSpeech 2024 TAUKADIAL Challenge, we study language markers from spontaneous speech in English and Chinese and use the bilingual language markers to identify MCI cases and predict the Mini-Mental Status Examination (MMSE) scores. Our proposed framework combines the power from 1) feature extraction of a comprehensive set of bilingual acoustic features, semantic and syntactic features from language models; 2) careful treatment of model complexity for small sample size; 3) consideration of imbalanced demographic structure, potential outlier removal, and a multi-task treatment that uses the prediction of clinical classification as prior for MMSE prediction. The proposed approach delivers an average of 78.2% Balanced Accuracy in MCI detection and an average RMSE of 2.705 in predicting MMSE.
  </details>  

* **Subject Harmonization of Digital Biomarkers: Improved Detection of Mild Cognitive Impairment from Language Markers** <br>
  <b> <u>Bao Hoang</u> </b>, Yijiang Pang, Hiroko Dodge, Jiayu Zhou. <br>
  [PSB 2024] <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11017207/" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/illidanlab/subject_harmonization" role="button" target="_blank"> Code </a> |
        <a href="../files/PSB2024Slide.pdf" role="button" target="_blank"> Slides </a>
    </summary>
  Mild cognitive impairment (MCI) represents the early stage of dementia including Alzheimer’s disease (AD) and is a crucial stage for therapeutic interventions and treatment. Early detection of MCI offers opportunities for early intervention and significantly benefits cohort enrichment for clinical trials. Imaging and in vivo markers in plasma and cerebrospinal fluid biomarkers have high detection performance, yet their prohibitive costs and intrusiveness demand more affordable and accessible alternatives. The recent advances in digital biomarkers, especially language markers, have shown great potential, where variables informative to MCI are derived from linguistic and/or speech and later used for predictive modeling. A major challenge in modeling language markers comes from the variability of how each person speaks. As the cohort size for language studies is usually small due to extensive data collection efforts, the variability among persons makes language markers hard to generalize to unseen subjects. In this paper, we propose a novel subject harmonization tool to address the issue of distributional differences in language markers across subjects, thus enhancing the generalization performance of machine learning models. Our empirical results show that machine learning models built on our harmonized features have improved prediction performance on unseen data.
  </details>  

* **Subject Harmonization of Multi-Modal Digital Markers: Improved Detection of Mild Cognitive Impairment Using Language and Facial Expression** <br>
  <b> <u>Bao Hoang</u> </b>, Yijiang Pang, Hiroko Dodge, Jiayu Zhou. <br>
  [AAIC 2024] (Abstract Submission) <br>
  <details> 
    <summary>
        <a href="https://alz.confex.com/alz/2024/meetingapp.cgi/Paper/86340" role="button" target="_blank"> Abstract </a> | 
        <a href="../files/AAIC24_Poster.pdf" role="button" target="_blank"> Poster </a>

    </summary>
  Mild Cognitive Impairment (MCI) is the prodromal stage of dementia, including Alzheimer’s Disease (AD). Early identification and accurate assessment of MCI are critical for clinical trial enrichment as well as the early intervention of AD. Digital makers offered a unique opportunity for ecologically valid and affordable early detection approaches. Language markers extracted from verbal communications have shown diagnostic efficacy in detecting early MCI. Recent studies have shown that in addition to semantic and syntactic information in dialogues, emotions in communication can also be helpful in early MCI detection. A joint analysis of language markers and emotion indicative of facial expression is thus of great interest. Features from emotion could have additional predictive benefits to language markers. One general challenge of digital biomarkers is that feature distributions are very distinct. We hereby conduct a multi-modal analysis of language and facial expression, combined with different harmonization.
  </details>  
  
* **Towards Stability of Parameter-free Optimization** <br>
  Yijiang Pang, Shuyang Yu,<b> <u>Bao Hoang</u> </b>, Jiayu Zhou. <br>
  [arXiv 2024] (Preprint)<br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2405.04376" role="button" target="_blank"> Paper </a> 
    </summary>
  Hyperparameter tuning, particularly the selection of an appropriate learning rate in adaptive gradient training methods, remains a challenge. To tackle this challenge, in this paper, we propose a novel parameter-free optimizer, \textsc{AdamG} (Adam with the golden step size), designed to automatically adapt to diverse optimization problems without manual tuning. The core technique underlying \textsc{AdamG} is our golden step size derived for the AdaGrad-Norm algorithm, which is expected to help AdaGrad-Norm preserve the tuning-free convergence and approximate the optimal step size in expectation w.r.t. various optimization scenarios. To better evaluate tuning-free performance, we propose a novel evaluation criterion, \textit{reliability}, to comprehensively assess the efficacy of parameter-free optimizers in addition to classical performance criteria. Empirical results demonstrate that compared with other parameter-free baselines, \textsc{AdamG} achieves superior performance, which is consistently on par with Adam using a manually tuned learning rate across various optimization tasks.
  </details>  

* **Cross-modality debiasing: using language to mitigate sub-population shifts in imaging** <br>
  Yijiang Pang,<b> <u>Bao Hoang</u> </b>, Jiayu Zhou. <br>
  [arXiv 2024] (Preprint)<br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2403.07888" role="button" target="_blank"> Paper </a> 
    </summary>
  Sub-population shift is a specific type of domain shift that highlights changes in data distribution within specific sub-groups or populations between training and testing. Sub-population shift accounts for a significant source of algorithmic bias and calls for distributional robustness. Recent studies found inherent distributional robustness in multi-modality foundation models, such as the vision-language model CLIP, yet this robustness is vulnerable through parameter fine-tuning. In this paper, we propose leveraging the connection of robustness among different modalities and reshaping the distributional robustness of one modality with another. Specifically, in the context of the distributional robustness of CLIP, we propose to leverage natural language inputs to debias the image feature representations, to improve worst-case performance on sub-populations. Our extensive empirical studies show that image representations debiased by natural language can achieve significant performance improvement and reduction of performance instability under sub-population shifts.
  </details>  

* **Data augmentation for small face datasets and face verification by generative adversarial networks inversion** <br>
  DT Nguyen, CT Tran, TT Nguyen, <b> <u>CB Hoang</u> </b>, BN Nguyen, PI Cheong. <br>
  [KSE 2021] <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://ieeexplore.ieee.org/abstract/document/9648720/" role="button" target="_blank"> Paper </a> 
    </summary>
   One of the most challenging issues in the utilisation of machine learning in face datasets is the lack of data, especially when there is inadequate collection of datasets. On one hand, the cost of collecting new face images could be very costly and it depend heavily on the resources and the availability of the data collection. On the other hand, insufficient face datasets could lead to over-fitting issues in any deep learning models especially in the face verification tasks as it requires adequate amount of face dataset. Nevertheless, Generative Adversarial Networks (GANs) offers a better way to augment the data by generating synthetic face images based on the close-distributed pixels of real images. With this intention, GAN inversion was introduced to produce better performance comparing to the previous GAN concepts; by inverting a given face image back into the latent space of a pretrained GAN model with low loss transmissions. This paper demonstrates the feasibility of GAN inversion during the face verification process. We will also illustrate the comparison between previous GAN models, and traditional machine learning augmentation methods in face images generation.
  </details>  

  

