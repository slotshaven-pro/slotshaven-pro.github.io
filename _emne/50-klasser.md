---
title: Klasser i python
description: '- og en lidt om OOP'
order: 50

---
Klasser definerer objekter, der _indkapsler_ data og funktionalitet.

### Attributter og metoder

En klasse har attributter (variable, egenskaber) og metoder (funktioner).

### Instans

En klasse er en slags _skabelon_. Når man bruger klassen i sin kode, skaber man en _instans_ af klassen.

## Nedarvning

Klasser kan nedarve fra andre klasser. På den måde kan man opbygge _klassehierakier_.

Man taler om superklasser og subklasser. Subklasser nedarver fra en superklasse.

## Klassestruktur

En klasse i Python defineres ved hjælp af nøgleordet `class`, efterfulgt af klassens navn.

```python
class ClassName:
    def __init__(self, parameter1, parameter2):
        self.attribute1 = parameter1
        self.attribute2 = parameter2

    def method1(self):
        # Implementering af metode

    def method2(self):
        # Implementering af metode
```

Lad os bryde komponenterne i en klasse ned:

- **`__init__`-metode (konstruktør)**: Dette er en speciel metode, der kaldes, når en instans af klassen oprettes. Den bruges til at initialisere klassens attributter. Parameteren `self` refererer til den instans, der bliver oprettet, og den bruges til at få adgang til klassens attributter og metoder inden for klassedefinitionen.

- **Attributter**: Attributter er variabler, der indeholder data, som er specifik for hver instans af klassen. De defineres inde i `__init__`-metoden ved hjælp af nøgleordet `self` efterfulgt af attributnavnet (f.eks. `self.attribute1 = parameter1`).

- **Metoder**: Metoder er funktioner, der er defineret inde i en klasse. De definerer adfærd og handlinger, som instanser af klassen kan udføre. En særlig ting i python er at metoder altid tager parameteren `self` som det første argument, hvilket gør det muligt for dem at få adgang til klassens attributter og andre metoder.

Lad os nu se på nogle kodeeksempler og forklaringer:

```python
class Pet:
    def __init__(self, name, species):
        self.name = name
        self.species = species

    def introduce(self):
        print(f"Hej, mit navn er {self.name}, og jeg er en {self.species}.")
```

I dette eksempel definerer vi en `Pet`-klasse med en `__init__`-metode, der tager `name` og `species` som parametre. Inde i `__init__`-metoden tildeler vi værdierne af `name` og `species` til instansens attributter `self.name` og `self.species`.

Vi definerer også en `introduce`-metode, der udskriver en besked, der introducerer kæledyrets navn og art.

```python
dog = Pet("Fido", "hund")
cat = Pet("Plet", "kat")
```

Her opretter vi to instanser af `Pet`-klassen: `dog` og `cat`. Vi angiver de nødvendige argumenter til konstruktøren (`name` og `species`), når vi opretter hver instans.

```python
dog.name  # Output: Fido
dog.species  # Output: hund
```

Man kan tilgå en instans' attributter ved hjælp af punktnotation - i dette eksempel  attributterne `name` og `species` for instansen `dog`.

```python
dog.introduce()  # Output: Hej, mit navn er Fido, og jeg er en hund.
cat.introduce()  # Output: Hej, mit navn er Plet, og jeg er en kat.
```

Endelig kalder vi metoden `introduce` på hver instans (`dog` og `cat`), som udskriver en kort beskrivelse af instansen.

Vi kan også tildele nye værdier til en instans attributter ved hjælp af punktnotation. I eksemplet opdaterer vi attributten `name` for instansen `dog` til "Max" og tildeler en ny attribut `color` med værdien "Brun".

```python
dog.name = "Max"
dog.color = "Brun"

dog.name  # Output: Max
dog.color  # Output: Brun
```

Efter at have opdateret attributterne kan vi få adgang til deres nye værdier ved hjælp af punktnotation. Attributten `name` for instansen `dog` er nu "Max", og den nytilføjede attribut `color` har værdien "Brun".
