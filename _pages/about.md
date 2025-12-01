---
permalink: /
title: "Pengrun Huang (黄鹏润)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am Pengrun Huang, a third-year Ph.D. student in the Computer Science and Engineering Department at the University of California, San Diego. I am fortunate to be co-advised by [Kamalika Chaudhuri](https://cseweb.ucsd.edu/~kamalika/) and [Yu-Xiang Wang](https://cseweb.ucsd.edu/~yuxiangw/). Previously, I earned my bachelor’s and master’s degrees in Honors Mathematics from University of Michigan. I was mentored by [Maggie Makar](https://mymakar.github.io/). 

I work on trustworthy ML, data privacy and confidentiality, with a current emphasis on large language models (LLMs). In particular, I am interested in:

- Identifying training data privacy and confidentiality risk.
- Measuring model memorization.
- Designing defense strategy for privacy attacks.


### Selected Publications
{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
