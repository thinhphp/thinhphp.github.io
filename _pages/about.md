---
permalink: /
title: "Welcome to Thinh's homepage!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi, I am a second-year PhD student at [Virginia Tech](https://cs.vt.edu/) (VT), advised by Prof. [Tu Vu](https://tuvllms.github.io/). My research focuses on effective and efficient methods to advance reasoning skills for search-augmented large language models and intelligent web search agents.

Previously, I spent 2 years working as an AI Resident at [VinAI Research](https://www.vinai.io/) under the supervision of Dr. [Dat Quoc Nguyen](https://datquocnguyen.github.io/). Prior to that, I completed my bachelor's degree in Computer Science at University of Science, Vietnam National University, Ho Chi Minh city.
<!-- I am deeply interested in natural language processing (NLP) and LLMs. I welcome the opportunity to expand my horizons and delve into new interesting topics. -->

<span style="color: green">🔎 Looking for an internship position in Summer 2026! Check out my CV</span> [here](/files/Thinh_CV.pdf)

## 🌟 Research interests
I am now focusing on improving LLMs' reasoning skills by injecting knowledge from external tools, including:
* **Search-augmented LLMs**: enhancing LLMs with search capabilities for more accurate and up-to-date knowledge.
* **Web search agents**: designing effective approaches to enable agents to find accurate information in noisy web environments.
* **Advanced reasoning**: developing methods to improve LLMs' ability to engage in sophisticated reasoning processes.

## 🔥 News and Highlights
* [2025/06] New [preprint](https://arxiv.org/abs/2506.01062) on a challenge benchmark for LLM reasoning over conflicting evidence.
* [2024/08] I started my PhD journey at Virginia Tech! 🎉
* [2023/12] 1 paper accepted to ICASSP 2024.
* [2023/11] 1 paper accepted to Findings of EMNLP 2023.
* [2023/05] 1 paper accepted to INTERSPEECH 2023.
* [2022/07] I joined VinAI Research as an AI Resident! 🎉

<a id='publications'></a>
## 📝 Selected Publications
Checkout my [Google Scholar](https://scholar.google.com/citations?hl=vi&user=BIfvNRUAAAAJ) for a up-to-date publication list.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}