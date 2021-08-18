---
permalink: /
title: "Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Howdy! I am a Master student from the Department of Computer Science and Engineering at Texas A&M University, working with Dr.Na Zou and Dr. [Xia (Ben) Hu](http://faculty.cs.tamu.edu/xiahu/). I received my Master degree in Industrial Engineering from Texas A&M University in 2020 and Bachelor degree in Logistics Engineering from Beijing University of Posts and Telecommunications.

I’m an engineer and researcher working at Data Lab of Texas A&M University, focusing on Anomaly Detection and Fairness AI. I am also a seasoned software developer working at Texas A&M Data Lab, contributed to several Python open-source projects with more than 1700 GitHub stars and more than 50,000 downloads in total.

<h1> Open-Source Projects </h1>
<img src="https://raw.githubusercontent.com/datamllab/tods/master/docs/img/tods_logo.png" width="200">
<h3 class="archive__item-title" itemprop="headline" style="font-weight:normal;"> TODS: An Automated Time-series Outlier Detection System (<b>>400 stars</b>) </h3>
Presented in <b>AAAI 2021</b>
<br>
<a href="https://tods-doc.github.io/">[Website]</a>
|
<a href="https://arxiv.org/pdf/2009.09822.pdf">[Paper]</a>
|
<a href="https://github.com/datamllab/tods">[Code]</a>
|
<a href="https://www.youtube.com/watch?v=H0bBXuDUe7s">[Video]</a>
<br>

<img src="https://daochenzha.github.io/files/rlcard/logo.jpg" width="200">
<h3 class="archive__item-title" itemprop="headline" style="font-weight:normal;"> RLCard: A Toolkit for Reinforcement Learning in Card Games (<b>>1,300 stars</b>) </h3>
<a href="http://rlcard.org/">[Website]</a>
|
<a href="https://daochenzha.github.io/files/rlcard-a-platform.pdf">[Paper]</a>
|
<a href="https://douzero.org/">[Demo]</a>
|
<a href="https://github.com/datamllab/rlcard">[Code]</a>
|
<a href="https://www.youtube.com/watch?v=krK2jmSdKZc">[Video]</a>
<br>
<img src="https://daochenzha.github.io/files/douzero-gif.gif" width="350">

<h1> Course Projects </h1>
under development

<h1> Publications </h1>

<b> * Equal contribution </b>

{% include base_path %}

{% assign cur_year = "9999" %}
{% for post in site.publications reversed %}
  {% assign dates = post.date | split: "-" %}
  {% assign year = dates.first %}
  {% if year != cur_year %}
    {% assign cur_year = year %}
<h2> {{ year }} </h2>
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

