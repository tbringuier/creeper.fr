---
layout: page
title: Applications
description: Une liste d'applications que j'auto-héberge chez moi !
---

<div class="service-grid">
  {% for service in site.data.services %}
    <a href="{{ service.url }}" class="service-card" target="_blank" rel="noopener noreferrer">
      <img src="/assets/services/{{ service.logo }}" alt="Logo de {{ service.name }}">
      <h3>{{ service.name }}</h3>
      <p>{{ service.description }}</p>
    </a>
  {% endfor %}
</div>
Cette page a été codée par [@louino](https://github.com/louino2478/), son site est disponible [ici](https://louino.fr/). Merci à lui ^w^ !
