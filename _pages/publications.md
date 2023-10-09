---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can also find the full list of my publicaiton at [Google Scholar Profile](https://scholar.google.com/citations?user=bqinFgYAAAAJ&hl=en&authuser=1).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Contrastive Learning
------
**HiCL: Hierarchical Contrastive Learning of Unsupervised Sentence Embeddings**<br>
<u>Zhuofeng Wu</u>, Chaowei Xiao, V. G. Vydiswaran<br>
*In Proceedings of Findings of EMNLP 2023*

**Clear: Contrastive learning for sentence representation**<br>
<u>Zhuofeng Wu</u>, Sinong Wang, Jiatao Gu, Madian Khabsa, Fei Sun, Hao Ma<br>
*arXiv preprint*<br>
[[Preprint](https://arxiv.org/pdf/2012.15466.pdf)]

## Prompt Tuning
------
**IDPG: An instance-dependent prompt generation method**<br>
<u>Zhuofeng Wu</u>, Sinong Wang, Jiatao Gu, Rui Hou, Yuxiao Dong, VG Vydiswaran, Hao Ma<br>
*In Proceedings of Findings of [NAACL 2022](https://2022.naacl.org/) (Oral Presentation)*<br>
[[Paper](https://aclanthology.org/2022.naacl-main.403.pdf)] [[Github](https://github.com/CSerxy/IDPG)] [[Video](https://underline.io/lecture/53933-idpg-an-instance-dependent-prompt-generation-method)]
 
## Robustness of ML model
------
**Defending against Insertion-based Textual Backdoor Attacks via Attribution.**<br>
Jiazhao Li, <u>Zhuofeng Wu</u>, Wei Ping, Chaowei Xiao, V. G. Vydiswaran.<br>
*In Proceedings of Findings of ACL 2023*<br>
[[Paper](https://aclanthology.org/2023.findings-acl.561.pdf)] [[Github](https://github.com/JiazhaoLi/AttDef)] 

**Chatgpt as an attack tool: Stealthy textual backdoor attack via blackbox generative model trigger**<br>
*arXiv preprint*<br>
[[Preprint](https://arxiv.org/pdf/2304.14475.pdf)]

## Diffusion Models for for Non-Autoregressive Generation
**PLANNER: Generating Diversified Paragraph via Latent Language Diffusion Model**<br>
*In Proceedings of NeurIPS 2023*<br>
[[Paper](https://arxiv.org/pdf/2306.02531.pdf)]

## Historical Language Change
**Identify Shifts of Word Semantics through Bayesian Surprise**<br>
*In Proceedings of SIGIR 2018 (Oral Presentation)*<br>
[[Paper](https://dl.acm.org/doi/pdf/10.1145/3209978.3210040)]
