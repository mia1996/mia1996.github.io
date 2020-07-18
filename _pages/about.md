---
permalink: /
title: "Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Howdy! I am a second-year PhD student from the Department of Computer Science and Engineering at Texas A&M University, working with [Dr. Xia (Ben) Hu](http://faculty.cs.tamu.edu/xiahu/). Prior to my study at Texas A&M, I received my Bachelor degree in Computer Science from Wuhan University, working with [Dr. Chenliang Li](http://www.lichenliang.net/).

My research interests lie in machine learning and data mining. I have been studying reinforcement learning and its applications. Recently, I am interested in optimizing data mining solutions with deep reinforcement learning, such as anomaly detection and graph neural networks. I am experienced in text mining, such as topic modeling and text classification. I have also been working on automated machine learning to provide accessable machine learning solutions.

I am an active open-source contributor. I strive to create easy-to-use tools to enable more people to benefit from machine learning and data mining algorithms. I am leading [RLCard](https://github.com/datamllab/rlcard), a toolkit for reinforcement learning in card games. I am also contributing to [PyODDS](https://github.com/datamllab/pyodds), an anomaly detection package with automated machine learning.

<h1> Publications </h1>

<a href="https://scholar.google.com/citations?user=RXp2tEwAAAAJ&hl=en"> [Google Schorlar] </a>
<br>
<b> * Equal contribution </b>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

