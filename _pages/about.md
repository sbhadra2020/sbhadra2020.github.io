---
permalink: /
title: ""
layout: single
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D candidate in Computer Science and Engineering at the Washington University in St. Louis. Currently, I am a visiting scholar at the University of Illinois at Urbana-Champaign in the [Computational Imaging Science Laboratory](https://anastasio.bioengineering.illinois.edu/) supervised by [Prof. Mark A. Anastasio](https://bioengineering.illinois.edu/people/maa). My research focuses on investigating deep learning (DL) methods for image reconstruction guided by fundamental principles of imaging science. Before joining my Ph.D program, I completed my Bachelor of Engineering (B.E.) degree in Electronics and Telecommunication Engineering from Jadavpur University, India in 2016. 

<!---
Inspired by https://giannisdaras.github.io/
-->
## News
* Paper on learning stochastic object models with advanced AmbientGANs accepted in SPIE Journal of Medical Imaging 2022 (to be published)
* Paper on finding multiple data-consistent solutions of ill-posed tomographic imaging problems with a style-based GAN available on arXiv [(preprint)](http://arxiv.org/abs/2202.05311)
* Research on hallucinations in medical imaging highlighted in IEEE Spectrum: [*Medical Image AIs Need a Good "Hallucination Map"*](https://spectrum.ieee.org/ai-medical-imaging-false-structures)
* Featured in research news by the Beckman Institute: [*Investigating medical imaging hallucinations*](https://beckman.illinois.edu/about/news/article/2022/01/07/investigating-medical-imaging-hallucinations)
* Paper defining hallucinations in ill-posed imaging inverse problems published in IEEE Transactions on Medical Imaging 2021 under the Second Special Issue on Machine Learning for Image Reconstruction [(paper)](https://ieeexplore.ieee.org/document/9424044)
* Paper on improved generative-model constrained image reconstruction with invertible neural networks published in IEEE Transactions on Computational Imaging 2021 [(paper)](https://ieeexplore.ieee.org/document/9318016)

## Selected publications
For a full and up-to-date list of my publications, please visit my [Google Scholar page](https://scholar.google.com/citations?user=vZQlZNwAAAAJ&hl=en).

{% include base_path %}

{% assign sorted = site.publications | reverse %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}



