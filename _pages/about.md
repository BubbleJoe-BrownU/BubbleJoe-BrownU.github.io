---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I am a data science master student at Brown University, where I work with Shekhar Pradhan and Ritambhara Singh at Conversational AI Lab as a research assistant. I am expected to graduate in 2024, and am actively applying for Ph.D. programs related to computer science, data science and artificial intelligence.

I have comprehensive knowledge on machine learning and deep learning algorithms and have implemented many of them, including but not limited to CNNs, RNNs, DGNs, GANs. I also implemented many Transformer based models, including Transformer, GPT, BERT, ViT, and plan to implement more in my ongoing project [TransformerHub](https://github.com/BubbleJoe-BrownU/TransformerHub). I have plenty of experiences with interacting with CLIP and GPT for zero-shot learning, generating pseudo labels, and conducting RLAIF, namely reinforce learning from AI feedback. I am also familiar with techniques that allows for today's large models to train and inference, like gradient accumulation, mixed precision training, distributed data parallelism, ZeRO parallelism, etc.

Previously, in 2022, I received my bachelor's degree with honors at <a href='http://ckc.zju.edu.cn/ckcen/wbout/list.htm'>Cho Kochen Honors College</a>, Zhejiang University. I also got a mini-minor certificate in computer science during 2021 - 2022.

Email: jiayu_zheng (at) brown.edu

My <a href='https://drive.google.com/file/d/1s-rXey7FF44fQ7-nKuw1CPvRphzxEUey/view'>CV</a> (up to August 2023) can be viewed here.

# 🔍 Current Research Interests

Currently I am conducting research on improving performance of language models by leveraging images as additional supervision signals at Conversational AI Lab. My research interests include three aspects. My research experience largely lies in computational linguistics, and vision-language models. My current research interests include
- (1) leveraging large language models and vision-language models to generate pseudo labels for unlabeled datasets or noisy datasets, which provides high-quantity and high-quality labels for fast delopyment of machine learning systems.
- (2) To make high-performance models more memory- and compute-efficient. There has been researchs in model compression, like knowledge distillation, to enable smaller student models to predict like large teacher models. And works like Sparse Transformer, Longformer and BigBird provide architectural innovations like shifted window attention and dilated attention, which reduce the formidable quadratic memory requirement of Transformer models from $O(N^2)$ to $O(log(N))$, even $O(N)$, without significant loss of performance.
- (3) To investigate large language models' and vision-language models' reasoning ability, especially compositional reasoning, on synthetic or real-world datasets. Large lanugage models, like GPT-4, display strong instruction following intelligence and, in the meanwhile, miserable reasoning ability. They perform poorly on math, easiy shift their response if you contradict them, and are not able to reverse their reasoning.


# 🔥 News
- *2023.06*: &nbsp;🎉🎉 Research intern at Conversational AI Lab, Brown University.
- *2022.09*: &nbsp;🎉🎉 I'll be joining Brown University as a data science MS student.
- *2022.06*: &nbsp;🎉🎉 Graduated from Zhejiang University as Outstanding Graduates.

# 📝 Publications and Projects
- *2023* [GourmAIt](https://github.com/BubbleJoe-BrownU/GourmAIt): Alleviate label noises with stochastic depth and Noisy Student Training.
- *2020* A Molecular Stereostructure Descriptor Based On Spherical Projection, Licheng Xu, Xin Li, Miaojiong Tang, Luotian Yuan, **Jiayu Zheng**, Shuoqing Zhang, Xin Hong

# 🎖 Honors and Awards
- *2022.05* Outstanding Graduates.
- *2021.10* Zhejiang University Scholarship, First Prize.
- *2019.10* Zhejiang University Scholarship, First Prize. 
- *2019.09* Outstanding Students. 

# 📖 Educations
- *2022.09 - Present*, *Sc.M* in Data Science, Data Science Institute, Brown University. 
- *2018.09 - 2022.06*, *Sc.B* in Chemistry with Honors, Cho KoChen Honors College, Zhejiang University. 

# 💬 Services
- *2023.09 - Present*, Teaching Assistant, CS1410 Artificial Intelligence, Brown University.
- *2022.03 - 2022.03*, Mentor for Women in Data Science (WiDS), Brown University.
- *2020.02 - 2020.10*, Undergraduate Head TA, Structural Chemistry, Zhejiang University.


# 💻 Internships
- *2023.06 - 2023.09*, Research Internship, Conversational AI Lab, Brown University.
