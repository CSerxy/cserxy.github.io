---
layout: archive
title: "Selected Publications by topics"
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

## LLM Pre-Training

**Clear: Contrastive learning for sentence representation**<br>
<u>Zhuofeng Wu</u>, Sinong Wang, Jiatao Gu, Madian Khabsa, Fei Sun, Hao Ma<br>
*arXiv preprint arXiv:2012.15466*<br>
[[Preprint](https://arxiv.org/pdf/2012.15466.pdf)]

## LLM Post-Trainig
------
### Parameter-Efficient Fine-Tuning:
**IDPG: An instance-dependent prompt generation method**<br>
<u>Zhuofeng Wu</u>, Sinong Wang, Jiatao Gu, Rui Hou, Yuxiao Dong, VG Vydiswaran, Hao Ma<br>
*In Proceedings of [NAACL 2022](https://2022.naacl.org/) (Oral Presentation)*<br>
[[Paper](https://aclanthology.org/2022.naacl-main.403)] [[Github](https://github.com/CSerxy/IDPG)] [[Video](https://underline.io/lecture/53933-idpg-an-instance-dependent-prompt-generation-method)]

### Contrastive Learning:
**HiCL: Hierarchical Contrastive Learning of Unsupervised Sentence Embeddings**<br>
<u>Zhuofeng Wu</u>, Chaowei Xiao, V. G. Vydiswaran<br>
*In Proceedings of Findings of EMNLP 2023*<br>
[[Paper](https://aclanthology.org/2023.findings-emnlp.161/)] [[Video](https://underline.io/lecture/90181-hicl-hierarchical-contrastive-learning-of-unsupervised-sentence-embeddings)]

### RAG:
**UniConv: Unifying Retrieval and Response Generation for Large Language Models in Conversations**<br>
Fengran Mo, Yifan Gao, Chuan Meng, Xin Liu, <u>Zhuofeng Wu</u>, Kelong Mao, Zhengyang Wang, Pei Chen, Zheng Li, Xian Li, Bing Yin, Meng Jiang<br>
*In Proceedings of [ACL 2025](https://2025.aclweb.org/)*<br>
[[Paper](https://aclanthology.org/2025.acl-long.344/)]

**Leveraging historical information to boost retrieval-augmented generation in conversations**<br>
Fengran Mo, Yifan Gao, <u>Zhuofeng Wu</u>, Xin Liu, Pei Chen, Zheng Li, Zhengyang Wang, Xian Li, Meng Jiang, Jian-Yun Nie<br>
*In [Information Processing & Management](https://www.sciencedirect.com/journal/information-processing-and-management)*<br>
[[Paper](https://www.sciencedirect.com/science/article/pii/S0306457325003905)]

## LLM Reasoning & Planning
------
**Divide-or-Conquer? Which Part Should You Distill Your LLM?**<br>
<u>Zhuofeng Wu</u>, He Bai, Aonan Zhang, Jiatao Gu, VG Vydiswaran, Navdeep Jaitly, Yizhe Zhang<br>
*In Proceedings of Findings of [EMNLP 2024](https://2024.emnlp.org/)*<br>
[[Paper](https://aclanthology.org/2024.findings-emnlp.145/)] [[Github](https://github.com/apple/ml-divide-or-conquer)]

## Historical Language Change
------
**Identify Shifts of Word Semantics through Bayesian Surprise**<br>
<u>Zhuofeng Wu</u>, Cheng Li, Zhe Zhao, Fei Wu, Qiaozhu Mei<br>
*In Proceedings of [SIGIR 2018](https://sigir.org/sigir2018/) (Oral Presentation)*<br>
[[Paper](https://dl.acm.org/doi/pdf/10.1145/3209978.3210040)] [[Github](https://github.com/CSerxy/IdentifyShifts)]
 
## Robustness of ML Models
------
**Defending against Insertion-based Textual Backdoor Attacks via Attribution.**<br>
Jiazhao Li, <u>Zhuofeng Wu</u>, Wei Ping, Chaowei Xiao, V. G. Vydiswaran.<br>
*In Proceedings of Findings of [ACL 2023](https://2023.aclweb.org/)*<br>
[[Paper](https://aclanthology.org/2023.findings-acl.561)] [[Github](https://github.com/JiazhaoLi/AttDef)] 

**Chatgpt as an attack tool: Stealthy textual backdoor attack via blackbox generative model trigger**<br>
Jiazhao Li, Yijin Yang, <u>Zhuofeng Wu</u>, V. G. Vydiswaran, Chaowei Xiao<br>
*In Proceedings of [NAACL 2024](https://aclanthology.org/2024.naacl-long.165.pdf)*<br>
*Spotlight Paper in [4th TrustNLP workshop](https://trustnlpworkshop.github.io/)*<br>
[[Paper](https://aclanthology.org/2024.naacl-long.165)]

## Diffusion Models
------
**PLANNER: Generating Diversified Paragraph via Latent Language Diffusion Model**<br>
Yizhe Zhang, Jiatao Gu, <u>Zhuofeng Wu</u>, Shuangfei Zhai, Josh Susskind, Navdeep Jaitly<br>
*In Proceedings of [NeurIPS 2023](https://neurips.cc/Conferences/2023)*<br>
[[Paper](https://arxiv.org/pdf/2306.02531.pdf)]
