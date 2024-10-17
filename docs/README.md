# Geometric formulas library

Geometric_lib is a python library containing multiple geometric formulas to make math implementation easier.
# Math formulas

## Circle

- ***Area function*** - returns area of the circle based on its radius
```python from circle import area

area(r)
```
- Example:
```python
area(10) # this will return 314.1592653589793
area(7) # this will return 153.93804002589985
```

- ***Perimeter function*** - returns perimeter of the circle based on its radius
```python
from circle import perimeter

perimeter(r)
```
  - Example:
  ```python
perimeter(10) # this will return 62.83185307179586
perimeter(7) # this will return 43.982297150257104
```

## Rectangle

- ***Area function*** - returns area of the rectangle based on its sides
```python
from rectangle import area

area(a, b)
```
- Example:
```python
area(10, 2) # this will return 20
area(7, 6) # this will return 42
```

- ***Perimeter function*** - returns perimeter of the rectangle based on its sides
```python
from rectangle import perimeter

perimeter(a, b)
```
  - Example:
  ```python
perimeter(10, 2) # this will return 24
perimeter(7, 6) # this will return 26
```

## Square

- ***Area function*** - returns area of the square based on its side
```python
from square import area

area(a)
```
- Example:
```python
area(10) # this will return 100
area(7) # this will return 49
```

- ***Perimeter function*** - returns perimeter of the square based on its side
```python
from square import perimeter

perimeter(a)
```
  - Example:
  ```python
perimeter(10) # this will return 40
perimeter(7) # this will return 28
```

## Triangle

- ***Area function*** - returns area of the square based on its base length and height
```python
from triangle import area

area(a, h)
```
- Example:
```python
area(10, 2) # this will return 10
area(7, 6) # this will return 21
```

- ***Perimeter function*** - returns perimeter of the square based on its sides
```python
from triangle import perimeter

perimeter(a, b, c)
```
  - Example:
  ```python
perimeter(10, 2, 10) # this will return 22
perimeter(7, 6, 5) # this will return 18
```

# Commit History

Latest to oldest:


"***fixed a typo in rectangle perimetr functio***" - klycennp 20.09.2024 (80c6571)

"***fixed a mistake in rectangle perimeter function***" - klycennp 20.09.2024 (211a637)

"***added triangle math functions***" - klycennp 20.09.2024 (8eee737)

"***added rectangle math functions***" -klycennp 20.09.2024 (44ce672)
