---
layout: xpage 
title: "Beginner Texts"
---

<div class="toc">
  <ul class="texts">
  {% for item in site.texts %}
  
    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
