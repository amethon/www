---
layout: reflection
title: "Inspired Cocktails"
categories: reflections
excerpt: cocktails inspired by abyssopelagia
---

<ul>
  {% for cocktail in site.cocktails %}
    <div>
      <h3><a href="{{ cocktail.url  | relative_url}}">{{ cocktail.title }}</a></h3>
      <img src="/www/assets/cocktails/{{ cocktail.image }}" alt="{{ cocktail.title }}" style="width:200px;height:200px;">
      <br>
      {{ cocktail.excerpt }}
    </div>
  {% endfor %}
</ul> 