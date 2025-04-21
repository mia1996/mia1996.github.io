---
permalink: /
title: "Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a <b>Machine Learning Infrastructure Engineer</b> at DocuSign Inc., focusing on <b>AI Search</b>. Before joining DocuSign, I was a Machine Learning Engineer at Neeva Inc., focusing on <b>large language modeling for web search</b>. I was a Master student from the Department of Computer Science and Engineering at Texas A&M University, working with Dr.[Na Zou](https://engineering.tamu.edu/etid/profiles/zou-na.html) and Dr. [Xia (Ben) Hu](http://faculty.cs.tamu.edu/xiahu/), graduated in <b>Dec 2022</b>.

I received my Master degree in Industrial Engineering from Texas A&M University in 2020 and Bachelor degree in Logistics Engineering from Beijing University of Posts and Telecommunications. I was a Data Analyst Intern at <b>Bristol-Myers Squibb</b> (Devens, MA) from 07/2019-12/2019 , working with [Christian Merrill](https://www.linkedin.com/in/christian-merrill-85186488/).

When I was an engineer and researcher working at Data Lab of Texas A&M University, I focus on <b>Anomaly Detection</b> and <b>Fairness AI</b>. I was also a seasoned software developer working at Texas A&M Data Lab, contributed to several Python open-source projects with more than <b>1700</b> GitHub stars and more than<b>50,000</b> downloads in total. <a href="https://mia1996.github.io/files/Resume_MingyangWan_2021.pdf">[Resume]</a>


<h1> Publications </h1>
<a href="https://scholar.google.com/citations?user=4vkJS7cAAAAJ&hl=en"> [Google Schorlar] </a>
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

<h1> Work Experience </h1>
<b>Machine Learning Infrastructure Engineer at DocuSign Inc. (San Francisco, CA)      07/2023-now <b>

  <img src="https://mia1996.github.io/files/docusign.jpg" width="200" class="center">

<b>Machine Learning Engineer at Neeva Inc. (Mountain View, CA)      01/2023-06/2023 <b>

  <img src="https://mia1996.github.io/files/neeva.jpg" width="100" class="center">

<h1> Intern/Co-op Experience </h1>
<b>Software Engineer, internship at Apple Inc. (Cupertino, CA)	    05/2022-08/2022</b>

<img src="https://mia1996.github.io/files/apple.jpg" width="70" class="center">

<b>Data Scientist, Co-Op at Bristol-Myers Squibb (Devens, MA)	    07/2019-12/2019</b>
<br>
<a href="https://mia1996.github.io/files/Recommendation_Letter.pdf">[Recommendation Letter]</a>
<br>
<img src="https://mia1996.github.io/files/Co-op.jpg" width="500" class="center">

<h1> Professional Service </h1>
<b> Conference Program Committee Member (45 reviews in total):</b>

2025 International Joint Conference on Artificial Intelligence (10 reviews). <br />
2025 International Joint Conference on Neural Networks (10 reviews).<br />
2025 Conference on Health, Inference, and Learning (2 reviews).<br />
2025 European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (3 reviews).<br />
2025 AAAI Conference on Artificial Intelligence (6 reviews for AI Agent for Information Retrieval Workshop, Preventing and Detecting LLM Misinformation Workshop).<br />
2025 International Conference on Learning Representations (7 reviews for Deep Generative Model in Machine Learning: Theory, Principle and Efficacy Workshop, AI for Nucleic Acids Workshop, GenAI Watermarking Workshop, Foundation Models in the Wild Workshop, XAI4Science: From Understanding Model Behavior to Discovering New Scientific Knowledge Workshop, AI for Children: Healthcare, Psychology, Education Workshop).<br />
2025 Teaching and Learning Conference (3 reviews).<br />
2025 IEEE/CVF Winter Conference on Applications of Computer Vision (3 reviews for Out-of-Label Hazards in Autonomous Driving Workshop).<br />
2025 IEEE International Conference on Electrical, Control and Computer Engineering (1 review).<br />

<b>Journal Reviewer (20 reviews in total): </b>

IEEE Transactions on Neural Networks and Learning Systems (provided 3 reviews).<br />
IEEE Transactions on Computational Social Systems (provided 2 reviews).<br />

<h1> Open-Source Projects </h1>
<!-- <img src="https://raw.githubusercontent.com/datamllab/tods/master/docs/img/tods_logo.png" width="200"> -->
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


<h1>Outside of Work</h1>
I have a cat named Oreo, born at the Aggieland shelter—he’s now 5 year old! He loves cuddles,tickles, and chicken dinner cans!

<img src="https://mia1996.github.io/files/oreo1.jpg" width="200">
<img src="https://mia1996.github.io/files/oreo2.jpg" width="200">
<img src="https://mia1996.github.io/files/oreo3.jpg" width="200">

On weekends, I volunteer with the Rabbit Team at the San Jose Animal Shelter, helping care for adorable bunnies. Let me know if you’re thinking about adopting one!

<img src="https://mia1996.github.io/files/bunny1.jpg" width="200">
<img src="https://mia1996.github.io/files/bunny2.jpg" width="200">
<img src="https://mia1996.github.io/files/bunny3.jpg" width="200">
<img src="https://mia1996.github.io/files/bunny4.jpg" width="200">

<!-- <h1> My cutie family </h1>

These are Oreo and ZhiZhi!<br>Oreo was born in the Aggieland Propertiesis shelter and is 1 year old now! He likes cuddles, tickles and dinner can!<br>Zhizhi likes hay donuts and playing by himself. He will say "zhi~" when he does not like you to touch him!

<img src="https://mia1996.github.io/files/pets.jpg" width="400"> -->

