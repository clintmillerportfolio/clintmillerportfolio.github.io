---
layout: page
title: portfolio
permalink: /portfolio/
---

{% for project in site.portfolio %}


<div class="project ">
 
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="img_scale" src="{{ project.img }}"/>
        {% else %}
        
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>

</div>

{% endif %}

{% endfor %}
