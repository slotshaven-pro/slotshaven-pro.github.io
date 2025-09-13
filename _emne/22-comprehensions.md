---
title: List comprehensions
description: '- alt på en linje'
order: 22

---
List comprehensions provide a concise way to create lists.
Common applications are to make new lists where each element is the result of some operation applied to each member of another sequence or iterable, or to create a subsequence of those elements that satisfy a certain condition.

Den lange form:
```
squares = []
for x in range(10):
    squares.append(x**2)

# squares = [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```

Den korte form med list comprehension
```
squares = [x**2 for x in range(10)]
```

Man kan tilføje flere for-løkker og betingelser!
```
[(x, y) for x in [1,2,3] for y in [3,1,4] if x != y]

```
Hvad gør denne linje? Den kombinerer to lister _hvis elementerne ikke er ens_!
Hvilket svarer til:
```
combs = []
for x in [1,2,3]:
    for y in [3,1,4]:
        if x != y:
            combs.append((x, y))

combs
[(1, 3), (1, 4), (2, 3), (2, 1), (2, 4), (3, 1), (3, 4)]
```

Man kan også generere dictionaries med list comprehensions.
```
keys = ['apple', 'banana', 'cherry']
values = [1.2, 0.5, 2.5]

dict = {keys[i]: values[i] for i in range(len(keys))}

print(dict)
{'apple': 1.2, 'banana': 0.5, 'cherry': 2.5}
```


