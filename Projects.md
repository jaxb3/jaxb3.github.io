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
    <br>
        <a href="{{ entry.url }}">
        <img src = "{{ site.url }}{{ entry.image }}" alt="Project logo"><br>
        </a>
    <br> 
{% endfor %}
</ul>
</h2>
