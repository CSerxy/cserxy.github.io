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

<font size=4>Contrastive Learning</font>
------
**HiCL: Hierarchical Contrastive Learning of Unsupervised Sentence Embeddings**<br>
<u>Zhuofeng Wu</u>, Chaowei Xiao, V. G. Vydiswaran<br>
*In Proceedings of Findings of EMNLP 2023*

**Clear: Contrastive learning for sentence representation**<br>
<u>Zhuofeng Wu</u>, Sinong Wang, Jiatao Gu, Madian Khabsa, Fei Sun, Hao Ma<br>
*arXiv preprint*<br>
[[Preprint](https://arxiv.org/pdf/2012.15466.pdf)]

<font size=5>Contrastive Learning</font>

## Prompt Tuning
------
**IDPG: An instance-dependent prompt generation method**<br>
<u>Zhuofeng Wu</u>, Sinong Wang, Jiatao Gu, Rui Hou, Yuxiao Dong, VG Vydiswaran, Hao Ma<br>
*In Proceedings of Findings of [NAACL 2022](https://2022.naacl.org/) (Oral Presentation)*
[[Paper](https://aclanthology.org/2022.naacl-main.403.pdf)] [[Github](https://github.com/CSerxy/IDPG)] [[Video](https://underline.io/lecture/53933-idpg-an-instance-dependent-prompt-generation-method)]
 
Robustness of ML model
======
**Defending against Insertion-based Textual Backdoor Attacks via Attribution.**<br>
Jiazhao Li, <u>Zhuofeng Wu</u>, Wei Ping, Chaowei Xiao, V. G. Vydiswaran.<br>
*In Proceedings of Findings of ACL 2023.*<br>
[[Paper](https://aclanthology.org/2023.findings-acl.561.pdf)] [[Github](https://github.com/JiazhaoLi/AttDef)] 

**Chatgpt as an attack tool: Stealthy textual backdoor attack via blackbox generative model trigger**<br>
*arXiv preprint*<br>
[[Preprint](https://arxiv.org/pdf/2304.14475.pdf)]


