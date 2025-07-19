---
title: Værktøjer
description: '- vi går ikke ned på tools'
permalink: /vaerktoejer
---
{% for item in site.data.vaerktoejer %}
  <section>
    <h2>{{ item.name }}</h2>
    <p>{{ item.description }}</p>
    <p><a href="{{ item.url }}" target="_blank" rel="noopener">{{ item.url }} ↗️</a></p>
    <p><strong>Kategori:</strong> {{ item.category }}</p>
  </section>
{% endfor %}