---
permalink: /
title: "Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Howdy! I am a third-year PhD student from the Department of Computer Science and Engineering at Texas A&M University, working with Dr. [Xia (Ben) Hu](http://faculty.cs.tamu.edu/xiahu/). Prior to my study at Texas A&M, I received my Bachelor degree in Computer Science from Wuhan University, working with Dr. [Chenliang Li](http://www.lichenliang.net/). I was a Research Intern at Seattle AI Lab of Kuai Inc., working with Dr. Wenye Ma and Dr. [Ji Liu](http://jiliu-ml.org/).

My research mainly focuses on machine learning and data mining. In particular, I am interested in reinforcement learning and its applications in automated, interpretable, and human-friendly machine learning systems. Beyond research, I strive to create easy-to-use open-source tools to enable more people to benefit from machine learning and data mining algorithms. I am leading [RLCard](https://github.com/datamllab/rlcard), a toolkit for reinforcement learning in card games (the project has attracted more than 700 stars and 150 forks). I am also co-leading [PyODDS](https://github.com/datamllab/pyodds), an end-to-end outlier detection system with automated machine learning, and [TODS](https://github.com/datamllab/tods), an automated time-series outlier detection system.

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

