---
permalink: /
title: "Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Howdy! I am a Master student from the Department of Computer Science and Engineering at Texas A&M University, working with Dr.[Na Zou](https://engineering.tamu.edu/etid/profiles/zou-na.html) and Dr. [Xia (Ben) Hu](http://faculty.cs.tamu.edu/xiahu/), expecting to graduate in <b>Dec 2022<b>. I'm a software engineer intern in <b>Apple Inc.<b>, working on an Automation testing system for Apple Apps organization.

I received my Master degree in Industrial Engineering from Texas A&M University in 2020 and Bachelor degree in Logistics Engineering from Beijing University of Posts and Telecommunications.I was a Data Analyst Intern at <b>Bristol-Myers Squibb<b> (Devens, MA) from 07/2019-12/2019 , working with [Christian Merrill](https://www.linkedin.com/in/christian-merrill-85186488/).

I’m an engineer and researcher working at Data Lab of Texas A&M University, focusing on <b>Anomaly Detection<b> and <b>Fairness AI<b>. I am also a seasoned software developer working at Texas A&M Data Lab, contributed to several Python open-source projects with more than <b>1700<b> GitHub stars and more than<b>50,000<b> downloads in total. <a href="https://mia1996.github.io/files/Resume_MingyangWan_2021.pdf">[Resume]</a>


<h1> Intern/Co-op Experience </h1>

Software Engineer, internship at Apple Inc. (Cupertino, CA)	05/2022-08/2022

<img src="https://mia1996.github.io/files/apple.jpg" width="70">

Data Scientist, Co-Op at Bristol-Myers Squibb (Devens, MA)	07/2019-12/2019
<br>
<a href="https://mia1996.github.io/files/Recommendation_Letter.pdf">[Recommendation Letter]</a>
<br>

<img src="https://mia1996.github.io/files/Co-op.jpg" width="600">


<h1> Open-Source Projects </h1>
<img src="https://raw.githubusercontent.com/datamllab/tods/master/docs/img/tods_logo.png" width="200">
<h3 class="archive__item-title" itemprop="headline" style="font-weight:normal;"> TODS: An Automated Time-series Outlier Detection System </h3>
Presented in <b>AAAI 2021</b>
<br>
<a href="https://github.com/datamllab/tods" class="svelte-bg3ukj"><img class="badge svelte-bg3ukj" alt="GitHub Repo stars" src="https://img.shields.io/github/stars/datamllab/tods"></a>
<a href="https://github.com/datamllab/tods" class="svelte-bg3ukj"><img class="badge svelte-bg3ukj" alt="GitHub Repo forks" src="https://img.shields.io/github/forks/datamllab/tods"></a>&nbsp;
<a href="https://tods-doc.github.io/">[Website]</a>
|
<a href="https://arxiv.org/pdf/2009.09822.pdf">[Paper]</a>
|
<a href="https://github.com/datamllab/tods">[Code]</a>
|
<a href="https://www.youtube.com/watch?v=H0bBXuDUe7s">[Video]</a>
<br>

<img src="https://daochenzha.github.io/files/rlcard/logo.jpg" width="200">
<h3 class="archive__item-title" itemprop="headline" style="font-weight:normal;"> RLCard: A Toolkit for Reinforcement Learning in Card Games</h3>
<a href="https://github.com/datamllab/rlcard" class="svelte-bg3ukj"><img class="badge svelte-bg3ukj" alt="GitHub Repo stars" src="https://img.shields.io/github/stars/datamllab/rlcard"></a>
<a href="https://github.com/datamllab/rlcard" class="svelte-bg3ukj"><img class="badge svelte-bg3ukj" alt="GitHub Repo forks" src="https://img.shields.io/github/forks/datamllab/rlcard"></a>&nbsp;
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


<h1> Publications </h1>
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

<h1> My cutie family </h1>

These are Oreo and ZhiZhi!<br>Oreo was born in the Aggieland Propertiesis shelter and is 1 year old now! He likes cuddles, tickles and dinner can!<br>Zhizhi likes hay donuts and playing by himself. He will say "zhi~" when he does not like you to touch him!

<img src="https://mia1996.github.io/files/pets.jpg" width="400">

