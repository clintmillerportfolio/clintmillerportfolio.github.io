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

<a href="/1_project/">
<img class="img_scale" src="img/nba_thumb.png"/>
</a>
<a href="/2_project/">
<img class="img_scale" src="img/thanks_thumb.png"/>
</a>
<a href="/3_project/">
<img class="img_scale" src="img/spy_thumb.png"/>
</a>
<a href="/4_project/">
<img class="img_scale" src="img/undead_thumb.png"/>
</a>
