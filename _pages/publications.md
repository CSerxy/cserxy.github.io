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

## Contrastive Learning
------
**HiCL: Hierarchical Contrastive Learning of Unsupervised Sentence Embeddings**<br>
<u>Zhuofeng Wu</u>, Chaowei Xiao, V. G. Vydiswaran<br>
*In Proceedings of Findings of [EMNLP 2023](https://2023.emnlp.org/)*<br>
[[Paper](https://arxiv.org/pdf/2310.09720.pdf)]

**Clear: Contrastive learning for sentence representation**<br>
<u>Zhuofeng Wu</u>, Sinong Wang, Jiatao Gu, Madian Khabsa, Fei Sun, Hao Ma<br>
*arXiv preprint arXiv:2012.15466*<br>
[[Preprint](https://arxiv.org/pdf/2012.15466.pdf)]

## Prompt Tuning
------
**IDPG: An instance-dependent prompt generation method**<br>
<u>Zhuofeng Wu</u>, Sinong Wang, Jiatao Gu, Rui Hou, Yuxiao Dong, VG Vydiswaran, Hao Ma<br>
*In Proceedings of [NAACL 2022](https://2022.naacl.org/) (Oral Presentation)*<br>
[[Paper](https://aclanthology.org/2022.naacl-main.403.pdf)] [[Github](https://github.com/CSerxy/IDPG)] [[Video](https://underline.io/lecture/53933-idpg-an-instance-dependent-prompt-generation-method)]

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
[[Paper](https://aclanthology.org/2023.findings-acl.561.pdf)] [[Github](https://github.com/JiazhaoLi/AttDef)] 

**Chatgpt as an attack tool: Stealthy textual backdoor attack via blackbox generative model trigger**<br>
Jiazhao Li, Yijin Yang, <u>Zhuofeng Wu</u>, V. G. Vydiswaran, Chaowei Xiao<br>
*arXiv preprint arXiv:2304.14475*<br>
[[Preprint](https://arxiv.org/pdf/2304.14475.pdf)]

## Diffusion Models
------
**PLANNER: Generating Diversified Paragraph via Latent Language Diffusion Model**<br>
Yizhe Zhang, Jiatao Gu, <u>Zhuofeng Wu</u>, Shuangfei Zhai, Josh Susskind, Navdeep Jaitly<br>
*In Proceedings of [NeurIPS 2023](https://neurips.cc/Conferences/2023)*<br>
[[Paper](https://arxiv.org/pdf/2306.02531.pdf)]
