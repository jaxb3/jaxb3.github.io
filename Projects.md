---
layout: page
title: Projects
permalink: /projects/
nav: true
---

Some of my more comprehensive academic and extracurricular projects.

<h2>
<ul>
{% for entry in site.data.projectlist.projects %}
    <li><a href="{{ entry.url }}"> {{ entry.title }}</a></li>
    
    <img src = "{{ site.url }}{{ entry.image }}" alt="Project logo"><br>
    <br> 
{% endfor %}
</ul>
</h2>
