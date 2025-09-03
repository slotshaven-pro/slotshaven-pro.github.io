---
title: Python
description: '- et programmeringssprog'
order: 1
---
Python er et open-source programmeringssprog med en enkel syntaks.

Python blev skabt af Guido van Rossum i 1991. Navnet henviser til den engelske komikergruppe Monty Python’s Flying Circus.

## Om sproget
Python er et **fortolket** sprog (interpreted language). Det vil sige at det skal ikke **kompileres** før det eksekveres.

Sporgets kernefunktioner er dog skrevet i C af hensyn til afviklingshastigheden.

Sproget benytter **dynamisk typing**. Det betyder, at datatyper bestemmes automatisk under kørsel.
Man skal altså ikke erklare dataytyper for variabler og argumenter.

Det benytter indrykning (fire mellemrum) til at gruppere kode - i steder for "{}" som i fx Java.

Bemærk indrykningen i linje 3-5.
```
x, y, swap = 10, 20, True
if swap:
     i = x
     x = y
     y = i
print(f"x = {x}, y = {y}")
```

## Biblioteker
Python beskrives ofte som et “batteries included”-sprog, fordi der findes velafprøvede biblioteker til stort set alt.
Det anvendes bredt af programmører og dataanalytikere i forskning og IT.

**Python Standard Library** (PSL) indeholder en lang række nyttige funktioner.

Derudover er der et bredt udvalg af tredjeparts-biblioteker til data science, matematik mv. - fx

- NumPy: effektiv lagring og beregning på flerdimensionelle arrays
- SciPy: numeriske værktøjer, fx integration og interpolation
- Pandas: DataFrame-struktur og metoder til manipulation og analyse af data
- Matplotlib: grafer og figurer i publikationsegnet kvalitet
- Scikit-Learn: værktøjskasse til almindelige maskinlæringsalgoritmer
- IPython / Jupyter: avanceret terminal og interaktiv notesbog til dataanalyse

I modsætning til PSL skal tredjepartsbiblioteker importeres før brug.

## Anvendelse
Som et højniveausprog kan Python i princippet anvendes til stort set alle formål.
Dets primære styrker ligger dog i data science, matematik og machine learning.

Det kan også anvendes til webudvikling (med fx flask).

Det kan dog generelt ikke anbefales til desktop-applikationer og spiludvikling da vindueshåndteringen er temmelig primitiv og ikke særlig pæn (i 2025).
