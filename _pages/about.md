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

Hi! I am a data science master's student at Brown University, where I am working with several amazing professors. I am working with Prof. [Stephen Bach](https://cs.brown.edu/people/sbach/) in the BATS Lab on adapting LLMs to out-of-distribution tasks in a parameter-efficient manner. I am also working with Prof. [Shekhar Pradhan](https://vivo.brown.edu/display/spradh15) and Prof. [Ritambhara Singh](https://ritambharasingh.com/) in the Conversational AI Lab on improving VLMs understanding of relations and orders. I am expected to graduate in 2024 and am actively applying for Ph.D. programs related to computer science, data science, and artificial intelligence.

I have comprehensive knowledge of machine learning and deep learning algorithms and have implemented many of them, including but not limited to CNNs, RNNs, DGNs, GANs. I also implemented many Transformer models, including Transformer, GPT, BERT, and ViT, and plan to implement more in my ongoing project [TransformerHub](https://github.com/BubbleJoe-BrownU/TransformerHub). I have plenty of experience with interacting with CLIP and GPT for zero-shot learning, generating pseudo labels, and conducting RLAIF, namely reinforcing learning from AI feedback. I am also familiar with techniques that allow today's large models to train and inference, like gradient accumulation, mixed precision training, distributed data parallelism, ZeRO parallelism, etc.

Previously, in 2022, I received my bachelor's degree with honors at <a href='http://ckc.zju.edu.cn/ckcen/wbout/list.htm'>Cho Kochen Honors College</a>, Zhejiang University. I also got a mini-minor certificate in computer science during 2021 - 2022.

Email: jiayu_zheng (at) brown.edu

To learn more about me, please check my <a href='https://bubblejoe-brownu.github.io/materials/jiayu_zheng_resume.pdf'>CV</a>.

# 🔍 Current Research Interests

My research experience largely lies in **Natural Language Processing (NLP)** and **Vision-Language Models (VLMs)**. Currently, I am doing research on improving language model performance by leveraging images as additional supervision signals at the Conversational AI Lab. My current research interests include three aspects:
- (1) To **make high-performance models more memory- and compute-efficient with better parallelism algorithms and model architectures**

[//]: <! This goal could be approached on both the algorithm side and the hardware side. There has been research in model compression, like knowledge distillation, to enable smaller student models to predict like large teacher models. Works like Sparse Transformer, Longformer, and BigBird provide architectural innovations like shifted window attention and dilated attention, which reduce the formidable quadratic memory requirement without significant loss of performance. On the hardware side, carefully managing KV cache and offloading part of the model to CPU RAM lead to significantly improved throughput during inference. >
- (2) To **investigate and improve large language models' and vision-language models' reasoning ability**

[//]: <! , especially compositional reasoning, on synthetic or real-world datasets. Large language models, like GPT-4, display strong instruction following intelligence and, in the meanwhile, miserable reasoning ability. They perform poorly on math, easily shift their response if you contradict them, and are not able to reverse their reasoning. >
- (3) To **improve large language models' and vision-language model's performance on downstream tasks parameter-efficiently**

[//]: <! Using soft prompts, i.e. caching a small, dataset-specific, learnable vocabulary for downstream tasks, can adapt large models towards specific domains, or remedy problems brought by subword-lebel tokenizers. This has proven to be effective in increasing LLM's performance in mathematical calculations, legal provision classification, or medical image classification tasks. >


# 🔥 News
- *2023.06*: &nbsp;🎉🎉 Research internship at Conversational AI Lab, Brown University.
- *2022.09*: &nbsp;🎉🎉 I'll be joining Brown University as a data science MS student.
- *2022.06*: &nbsp;🎉🎉 Graduated from Zhejiang University as Outstanding Graduates (rank 2% among a cohort of 101 students).

# 📝 Publications and Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Project 2023</div><img src='images/noisy_student.png' alt="sym" width="75%"></div></div>
<div class='paper-box-text' markdown="1">

[GourmAIt: Training Robust Deep Neural Networks on Noisy Datasets](https://github.com/BubbleJoe-BrownU/GourmAIt)

**Jiayu Zheng**

[[project page](https://github.com/BubbleJoe-BrownU/GourmAIt)]

- Implemented Noisy Student Training, where pseudo labels generated by a teacher model are used to train a
larger-or-equal-size student model, which becomes the teacher model in the next iteration
- Implemented stochastic depth, stepwise unfreezing scheduling, and learning rate scheduling to maximize the performance gain in finetuning ResNet
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Synlett 2020</div><img src='images/chem_research_pic.png' alt="sym" width="75%"></div></div>
<div class='paper-box-text' markdown="1">

[A Molecular Stereostructure Descriptor Based On Spherical Projection](https://www.thieme-connect.com/products/ejournals/pdf/10.1055/s-0040-1705977.pdf)

Licheng Xu, Xin Li, Miaojiong Tang, Luotian Yuan, **Jiayu Zheng**, Shuoqing Zhang, Xin Hong

[[project page](https://github.com/licheng-xu-echo/SPMS)]    [[paper](https://www.thieme-connect.com/products/ejournals/pdf/10.1055/s-0040-1705977.pdf)]
</div>
</div>

# 🎖 Honors and Awards
- *2022.06* Outstanding Graduates of Zhejiang University
- *2021.10* Cho Kochen Honors College Scholarship for Innovation
- *2021.10* Zhejiang University Scholarship, First Prize
- *2020.10* Cho Kochen Honors College Scholarship for Innovation
- *2020.10* Zhejiang University Scholarship, Third Prize
- *2019.10* Zhejiang University Scholarship, First Prize 
- *2019.09* Outstanding Students. 

# 📖 Educations
- *2022.09 - Present*, *Sc.M.* in Data Science, Data Science Institute, Brown University. 
- *2018.09 - 2022.06*, *Sc.B.* in Chemistry with Honors, Cho KoChen Honors College, Zhejiang University. 

# 💬 Services
- *2023.09 - Present*, Teaching Assistant, CS1410 Artificial Intelligence, Brown University.
- *2022.03 - 2022.03*, Mentor for Women in Data Science (WiDS), Brown University.
- *2020.02 - 2020.10*, Head Teaching Assistant, Structural Chemistry and Spectroscopy, Zhejiang University.


# 💻 Internships
- *2023.06 - 2023.09*, Research Internship, Conversational AI Lab, Brown University.
