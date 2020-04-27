---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

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
