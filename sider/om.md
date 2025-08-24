---
title: Valgfag Programmering B
description: '- kode og udvikling på HTX'
published: yes
permalink: /om
---
## Om faget
Programmering B er et studieretningsfag på MAT-PRO-linjen på HTX Slotshaven.

### Faglige mål
Eleverne skal kunne:

- bruge programmering til at undersøge et emne eller problemområde, med henblik på – via programmets funktion - at skabe
ny indsigt eller til at løse et problem
- behandle problemstillinger i samspil med andre fag
̶- anvende avancerede konstruktioner i et programmeringssprog
- redegøre for arkitekturen af programmer på forskellige abstraktionsniveauer, herunder relationen mellem brug og funktion
- redegøre for simple specifikationsmodeller og realisere disse i simple velstrukturerede programmer samt teste disse
- rette, tilpasse og udvide avancerede programmer
- demonstrere viden om fagets identitet og metoder
- arbejde inkrementelt og systematisk i programmeringsprocessen.

## Kernestof
Gennem kernestoffet skal eleverne opnå faglig fordybelse, viden og kundskaber.
Kernestoffet er:
- programmeringssprog og elementer i programmers opbygning, herunder variabler, typer, udtryk, kontrolstrukturer,
parametrisering/abstraktionsmekanismer, rekursion, polymorfi og algoritmemønstre
- arkitekturen for programmers interaktion med omgivelserne med henblik på hændelsesstyret interaktion og interaktion
mellem systemer
- generiske programdele og biblioteksmoduler
- arbejdsgange og systematik i programmeringsprocessen, herunder test og fejlfinding
- abstrakte programmeringsbeskrivelser og dokumentation.

## Didaktiske principper
Undervisningen organiseres omkring flere temaer og projekter. Disse vælges, så de tilsammen dækker kernestof og
supplerende stof, med henblik på at der er en klar progression i arbejdet med faglige mål og selvstændighed.

Undervisningen tilrettelægges ved brug af anerkendte didaktiske principper, herunder
- _use-modify-create_-progression fra at anvende udleverede programmer til at modificere disse for til sidst selvstændigt at skabe (nye dele af) programmer
- _Stepwise Improvement_, som teknik til trinvis, iterativ og systematisk udvikling af programmer, og
- _Worked Examples_ (kombineret med _faded guidance_), til illustration af eksemplariske løsningsprocesser.

Undervisningsformen differentieres således, at alle elever udvikler sig i undervisningsforløbet. Der veksles mellem overbliksskabende forløb, eksperimenter, øvelser og projekter.

## Eksamen
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
