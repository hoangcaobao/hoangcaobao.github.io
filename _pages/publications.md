---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Before Ph.D.
======
* **Distributed Harmonization: Federated Clustered Batch Effect Adjustment and Generalization** <br>
  <u>Bao Hoang</u>, Yijiang Pang, Siqi Liang, Liang Zhan, Paul Thompson, Jiayu Zhou. <br>
  [KDD 2024] (Oral Presentation) <br>
  <details> 
    <summary>
        Abstract |
        <a href="https://arxiv.org/pdf/2405.15081" role="button" target="_blank"> Paper </a> | 
        <a href="https://github.com/xiaoyuxin1002/UQ-PLM" role="button" target="_blank"> Code </a>
    </summary>
   Independent and identically distributed (i.i.d.) data is essential to many data analysis and modeling techniques. In the medical domain, collecting data from multiple sites or institutions is a common strategy that guarantees sufficient clinical diversity, determined by the decentralized nature of medical data. However, data from various sites are easily biased by the local environment or facilities, thereby violating the i.i.d. rule. A common strategy is to harmonize the site bias while retaining important biological information. The ComBat is among the most popular harmonization approaches and has recently been extended to handle distributed sites. However, when faced with situations involving newly joined sites in training or evaluating data from unknown/unseen sites, ComBat lacks compatibility and requires retraining with data from all the sites. The retraining leads to significant computational and logistic overhead that is usually prohibitive. In this work, we develop a novel Cluster ComBat harmonization algorithm, which leverages cluster patterns of the data in different sites and greatly advances the usability of ComBat harmonization. We use extensive simulation and real medical imaging data from ADNI to demonstrate the superiority of the proposed approach.
  </details>  
  

  

