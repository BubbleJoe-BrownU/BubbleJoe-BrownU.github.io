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

Hi! I am a data science master student at Brown University. I am expected to graduate in 2024, and am looking forward to apply for Ph.D. programs related to computer science, data science and artificial intelligence. If you are looking for a Ph.D. student, I would sincerely appreciate it if you could consider me as a candidate!

My research experience largely lies in computational linguistics, computer vision and vision-language models. I had research experience with building language models with image embeddings as additional supervision signals. I also implemented Transformer-like, GPT-like, and BERT-like models in my project, TransformerHub. In computer vision, I have implemented several well-known architectures like ConvNet, C-RNN, ViT, and Noisy Student Training, and also have plenty experience with evaluating models on datasets like ImageNet1K, MSCOCO, and etc. I am also familiar with some technique designs that make today's large models work, like gradient clipping, mixed precision training, self training, data parallelism, model parallelism, etc.

My research interests include three aspects. (1) To make high-performant models more memory- and compute-efficient. There has been efforts like knowledge distillation to enable smaller student models to behave like large teacher models, which is critical for advanced models and algorithms to be deployed in resource-insufficient systems. There are also works like Sparse Transformer, Longformer and BigBird which use shifted window attention mechanism and dilated attention mechanism, which, combined with global attention, to reduce the memory requirement of Transformer models from $O(N^2)$ to $O(log(N))$, even $O(N)$, without significant loss of performance. (2) To develop new pretraining tasks which increase data-efficiency of large scale pretraining on web crawled data. (3) 

Previously, in 2022, I received my bachelor's degree with honors at <a href='http://ckc.zju.edu.cn/ckcen/wbout/list.htm'>Cho Kochen Honors College</a>, Zhejiang University. I also got a mini-minor in computer science during 2021 - 2022.

Email: {first-name} _ {last-name} @ brown.edu
<a href='https://drive.google.com/file/d/1s-rXey7FF44fQ7-nKuw1CPvRphzxEUey/view'>CV</a>




# 🔥 News
- *2023.06*: &nbsp;🎉🎉 Research intern at Conversational AI Lab, Brown University.
- *2022.09*: &nbsp;🎉🎉 I'll be joining Brown University as a DS MS student.
- *2022.06*: &nbsp;🎉🎉 Graduated from Zhejiang University as Outstanding Graduates.

# 📝 Publications

# 🎖 Honors and Awards
- *2022.05* Outstanding Graduates.
- *2021.10* Zhejiang University Scholarship, First Prize.
- *2019.10* Zhejiang University Scholarship, First Prize. 
- *2019.09* Outstanding Students. 

# 📖 Educations
- *2022.09 - Present*, *Sc.M* in Data Science, Data Science Institute, Brown University. 
- *2018.09 - 2022.06*, *Sc.B* in Chemistry with Honors, Cho KoChen Honors College, Zhejiang University. 

# 💬 Experiences
- *2023.06 - 2023.09*, Research intern at Conversational AI Lab, Brown University.
- *2022.03*, Invited mentor for Women in Data Science (WiDS) at Brown University.
- *2020.02 - 2020.10*, Undergraduate Head TA at Zhejiang University.


# 💻 Internships
- *2023.06 - 2023.09*, Research Internship, Conversational AI Lab, Brown University.
