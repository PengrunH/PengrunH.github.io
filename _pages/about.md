---
permalink: /
title: "Pengrun Huang (黄鹏润)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am Pengrun Huang, a fourth-year Ph.D. student in the Computer Science and Engineering Department at the University of California, San Diego. I am fortunate to be co-advised by [Kamalika Chaudhuri](https://cseweb.ucsd.edu/~kamalika/) and [Yu-Xiang Wang](https://cseweb.ucsd.edu/~yuxiangw/). Previously, I earned my bachelor’s and master’s degrees in Honors Mathematics from University of Michigan. I was mentored by [Maggie Makar](https://mymakar.github.io/). 

My research centers on the privacy and confidentiality of large language models (LLMs), from risk identification to defense. I am broadly interested in auditing what LLMs leak about their training data, developing principled metrics to measure memorization, and designing provable defense mechanisms to protect data privacy and detect unauthorized use.


### Selected Publications
{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
