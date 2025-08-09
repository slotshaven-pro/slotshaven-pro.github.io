---
title: Valgfag Programmering B
description: '- kode og udvikling på HTX'
published: yes
permalink: /om
---
## Indledning
Programmering B er et studieretningsfag på MAT-PRO-linjen på HTX Slotshaven.


## Om faget
TODO

[Læs mere om eksamen ↗️]({% link sider/eksamen.md %}).

## Læreplaner
Undervisningen følger Undervisningsministeriets læreplaner som kan findes her.

{% for item in site.data.links %}
{% if item.source == "uvm" %}

### {{ item.name }}

{{ item.description }}

[↗️ PDF]({{ item.link }}){:target="_blank" rel="noopener"}

{% endif %}
{% endfor %}

## Grundbøger
{% include eboeger.html %}

## Bogmærker
Se også [bogmærker]({% link sider/bogmaerker.md %}).
