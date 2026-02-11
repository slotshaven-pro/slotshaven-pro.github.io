---
title: List comprehensions
description: '- alt på en linje'
permalink: /comprehensions
order: 22

---
List comprehensions er en præcis, kortfattet og meget _pythonic_ måde at oprette lister på.
En typisk praksi er at oprette nye lister som er resultatet af en operation på hvert element i en anden liste eller _iterable_, eller et subsæt af disse som opfylder et givet kriterium.

Sammenlign den lange form her ...

``` python
squares = []
for x in range(10):
    squares.append(x**2)

# squares = [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```

... med den korte form med list comprehension

``` python
squares = [x**2 for x in range(10)]
```

Lidt nemmere, hvar?

Man kan tilføje flere for-løkker og betingelser.

``` python
[(x, y) for x in [1,2,3] for y in [3,1,4] if x != y]
```

Hvad gør denne linje? Den kombinerer to lister _hvis elementerne ikke er ens_!
Hvilket i lang form svarer til:

``` python
combs = []
for x in [1,2,3]:
    for y in [3,1,4]:
        if x != y:
            combs.append((x, y))

# combs = [(1, 3), (1, 4), (2, 3), (2, 1), (2, 4), (3, 1), (3, 4)]
```
Bemærk at output er en liste af tupler.

Man kan også generere dictionaries.

``` python
keys = ['apple', 'banana', 'cherry']
values = [1.2, 0.5, 2.5]
# Build dictionary
dict = {keys[i]: values[i] for i in range(len(keys))}

# dict = {'apple': 1.2, 'banana': 0.5, 'cherry': 2.5}
```
