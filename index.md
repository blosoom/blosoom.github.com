---
layout: page
title: Blosoom
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
      <li>
          <h2>
              <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
          </h2>
          <span> {{ post.description }} </span>
      </li>       
  {% endfor %}
</ul>

    

