---
layout: archive
title: "Publications [(Google Scholar Profile)](https://scholar.google.com/citations?user=ysA5F_kAAAAJ&hl=en&authuser=1)"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
<b>[A marine magnetotelluric coast effect sensitive to the lithosphere-asthenosphere boundary](http://lantaoyu.com/publications/TextDR)</b> <br> 
<b>Wang, S.</b>, Constable, S., Reyes-Ortega, V., Rychert, C.A.
<i>The 23rd International Conference on Artificial Intelligence and Statistics</i>. <b>AISTATS 2020</b>.
