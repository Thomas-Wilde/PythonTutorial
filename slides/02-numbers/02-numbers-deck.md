---
title:        Python Tutorial
subtitle:     Zahlen
author:       Dr. Tom
deck-id:  'python-numbers'
...

--------------------------------------------------------------------------------

# Bisher hatten wir `Strings`

::: incremental
:::small
1. ``` {python}
   print("Hallo wie geht's Dir?")
   ```
   `"Hallo wie geht's Dir?"` ist ein **`String`**
2. ``` {python}
   print('Hallo wie geht's Dir?')
   ```
   `'Hallo wie geht's Dir?'` ist auch ein **`String`**
:::
:::

--------------------------------------------------------------------------------

# Jetzt kommen Zahlen

--------------------------------------------------------------------------------

# Python hat 3 Typen für Zahlen

::: incremental
1. Ganze Zahlen $\mathbb{Z}$
   - Integer
   - 1, 5, 10, 2022, -314, 123456789
2. Reelle Zahlen $\mathbb{R}$
   - Float
   - 1.0, -1.0, 5.0, 10.99997
   - 3.141592 $\approx\Pi$
   - 1.414213 $\approx\sqrt{2}$
3. Komplexe Zahlen $\mathbb{C}$
:::

--------------------------------------------------------------------------------

# Beispiele für Integer

```
print(1)
print(5)
print(10)
print(2022)
print(-314)
print(123456789)
```

.

--------------------------------------------------------------------------------

# Beispiele für Integer

```
print(1)
print(5)
print(10)
print(2022)
print(-314)
print(123456789)
```

Integer Zahlen können in Python3 beliebig groß sein

--------------------------------------------------------------------------------

# Beispiele für Float

```
print(1.0)
print(-1.0)
print(5.0)
print(-5.0)
print(10.999997)
print(-10.999997)
```
.

--------------------------------------------------------------------------------

# Rechnen mit Zahlen - I

| Operation | Symbol | Integer | Float |
| :-------- | :----: | :-----: | :---- |
| Addition  |  `+`   |   ✅    | ✅    |


```
print(3 + 4)
print(1.0 + 7.5)
```
--------------------------------------------------------------------------------

# Rechnen mit Zahlen - II

| Operation   | Symbol | Integer | Float |
| :---------- | :----: | :-----: | :---- |
| Addition    |  `+`   |   ✅    | ✅    |
| Subtraktion |  `-`   |   ✅    | ✅    |

```
print(3 - 4)
print(1.0 - 7.5)
```

--------------------------------------------------------------------------------

# Rechnen mit Zahlen - III

| Operation   | Symbol | Integer | Float |
| :---------- | :----: | :-----: | :---- |
| Addition    |  `+`   |   ✅    | ✅    |
| Subtraktion |  `-`   |   ✅    | ✅    |
| Multiplikation      |  `*`   |   ✅    | ✅    |

```
print(3 * 4)
print(3.0 * 7.0)
```

--------------------------------------------------------------------------------

# Rechnen mit Zahlen - IV

| Operation   | Symbol | Integer | Float |
| :---------- | :----: | :-----: | :---- |
| Addition    |  `+`   |   ✅    | ✅    |
| Subtraktion |  `-`   |   ✅    | ✅    |
| Multiplikation      |  `*`   |   ✅    | ✅    |
| Division            |  `/`   |  (✅)   | ✅    |

```
print(12 / 4)
print(12 / 5)
print(12.0 / 4.0)
```

--------------------------------------------------------------------------------

# Rechnen mit Zahlen - V

| Operation   | Symbol | Integer | Float |
| :---------- | :----: | :-----: | :---- |
| Addition    |  `+`   |   ✅    | ✅    |
| Subtraktion |  `-`   |   ✅    | ✅    |
| Multiplikation      |  `*`   |   ✅    | ✅    |
| Division            |  `/`   |  (✅)   | ✅    |
| Division (abrunden) |  `//`  |   ✅    | ✅    |

```
print(12 // 5)
print(12.0 // 5.0)
```

--------------------------------------------------------------------------------

# Rechnen mit Zahlen - VI

| Operation   | Symbol | Integer | Float |
| :---------- | :----: | :-----: | :---- |
| Addition    |  `+`   |   ✅    | ✅    |
| Subtraktion |  `-`   |   ✅    | ✅    |
| Multiplikation      |  `*`   |   ✅    | ✅    |
| Division            |  `/`   |  (✅)   | ✅    |
| Division (abrunden) |  `//`  |   ✅    | ✅    |
| Division mit Rest   |  `%`   |   ✅    | ❌    |

```
print(12 % 4)
print(12 % 5)
print(12 % 6)
print(12 % 7)
```

--------------------------------------------------------------------------------

# Rechnen mit Zahlen

| Operation           | Symbol | Integer | Float |
| :------------------ | :----: | :-----: | :---- |
| Addition            |  `+`   |   ✅    | ✅    |
| Subtraktion         |  `-`   |   ✅    | ✅    |
| Multiplikation      |  `*`   |   ✅    | ✅    |
| Division            |  `/`   |  (✅)   | ✅    |
| Division (abrunden) |  `//`  |   ✅    | ✅    |
| Division mit Rest   |  `%`   |   ✅    | ❌    |

--------------------------------------------------------------------------------

# Integer und Float mischen

- wenn `Integer` und `Float` gemischt werden, dann ist das Ergebnis `Float`

```
print(1 + 2.0)
print(3.0 + 4)
print(12 % 6)
print(12 % 7)
```

--------------------------------------------------------------------------------

# Strings und Zahlen kombinieren

- `String` und `Integer` bzw. `Float` können mit `+` angehängt werden.
```
print("5 + 6 = " + 5 + 6)
print("7 - 5 = " + 7 - 5)
print("3 * 5 = " + 3 * 5)
print("2 / 3 = " + 2 / 3)
print("9 // 4 = " + 9 // 4)
print("10 % 6 = " + 10 % 6)

print("1.265 + 3.1449 = "  1.265 + 3.1449 )
print("4.894 - 8.9577 = "  4.894 - 8.9577 )
print("7.023 * 9.8748 = "  7.023 * 9.8748 )
print("8.652 / 4.4413 = "  8.652 / 4.4413 )
print("21.01 // 6.9523 = " 21.01 // 6.9523)
```