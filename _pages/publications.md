---
layout: archive
title: "Publications [(Google Scholar)](https://scholar.google.com/citations?user=ysA5F_kAAAAJ&hl=en&authuser=1)" 
permalink: /publications/ 
author_profile: true
---

{% if author.googlescholar %}
   You can also find my articles on <u><a href="{{author.googlescholar}}">Google Scholar profile</a>.</u> 
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
<b>[A marine magnetotelluric coast effect sensitive to the lithosphere-asthenosphere boundary](https://academic.oup.com/gji/article-abstract/218/2/978/5485642)</b> <br> 
<b>Wang, S.</b>, Constable, S., Reyes-Ortega, V., Rychert, C.A.
<i>Geophysical Journal International</i>. <b>2019</b>.
