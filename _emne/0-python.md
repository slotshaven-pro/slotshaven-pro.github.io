---
title: Python
description: '- et programmeringssprog'
order: 1
---
Python er et open-source programmeringssprog med en enkel syntaks.

Python blev skabt af Guido van Rossum i 1991. Navnet henviser til den engelske komikergruppe Monty Python’s Flying Circus.

## Om sproget
Python er et **fortolket** sprog (interpreted language). Det vil sige at det skal ikke **kompileres** før det eksekveres.

Sprogets kernefunktioner er dog skrevet i C af hensyn til afviklingshastigheden.

Sproget benytter **dynamisk typing**. Det betyder, at datatyper bestemmes automatisk under kørsel.
Man skal altså ikke erklare datatyper for variabler og argumenter.

En særlig egenskab ved Python er **significant whitespace** - man bruger mellemrum eller indrykning til at samle kode i blokke - altså gruppere kode. Det er i modsætning til de fleste andre sprog som benytter et særligt tegn, fx "{}" som i fx Java eller C#.

Standard-indrykning er 4 mellemrum.

Bemærk altså at mellemrum og indrykning er meget vigtige - det er en del af syntaksen.

Bemærk indrykningen i linje 3-5.

``` python
1. x, y, swap = 10, 20, True
2. if swap:
3.      i = x
4.      x = y
5.      y = i
6. print(f"x = {x}, y = {y}")
7. # resultat
8. x = 20, y = 10
```

## Biblioteker

Python beskrives ofte som et “batteries included”-sprog, fordi der findes et bredt udvalg af velafprøvede biblioteker til alle formål.

**Python Standard Library** (PSL) indeholder en lang række nyttige funktioner.

Dertil kommer en række tredjeparts-biblioteker til data science, matematik mv.

Der kan nævnes:

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

Det kan dog sagtens også anvendes til webudvikling med fx flask.

Det kan dog generelt ikke anbefales til desktop-applikationer og spiludvikling da vindueshåndteringen er temmelig primitiv og mildest talt ikke særligt pæn efter 2025-standarder.

## Afvikling

Der er (mindst) fire måder at afvikle python på.

1. Python-fortolker
2. Scripts (.py-filer)
3. Jupyter notebook
4. IPython-fortolker

Desuden kan man i VS Code med python-udvidelsen bruge "pilen" til at eksekvere den åbne fil på.
