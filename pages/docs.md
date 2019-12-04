---
layout: page
title: Documentation
permalink: /docs/
---

# Documentation

Welcome! This website is dedicated to the documentation of the progress of SBME 2021's team 15 work. Please refer to the links below to find our more.

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
