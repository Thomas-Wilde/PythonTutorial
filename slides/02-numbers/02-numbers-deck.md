---
title:        Python Tutorial
subtitle:     Zahlen
author:       Dr. Thomas Wilde
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
print(-10.999997)
```

--------------------------------------------------------------------------------

# Python kennt 3 Typen für Zahlen  {#example-multicolumn layout="columns"}

### $~~~~~~\mathbb{Z}$ - Integer {.left}

1

5

10

2022

149600000

-314


## $\mathbb{R}$ - Float {.center}

1.0

-1.0

5.0

-10.999997

3.141592 $\approx\Pi$

1.414213 $\approx\sqrt{2}$

## $\mathbb{C}$ - Complex {.right}

Die interessieren uns erst im Abi oder beim Studium.

--------------------------------------------------------------------------------

# Rechnen mit Zahlene {#example-multicolumn layout="columns"}


### \mathbb{Z}$ - Integer {.left}


## $\mathbb{R}$ - Float {.right}

# Test


| Operation         | Integer | Float                            |    Reading     | Book    |
| :---------------- | :-----: | :------------------------------- | :------------: | ------- |
| Addition          |    +    | Course Introduction              |    Chapt. 1    | Physics |
| Subtraktion       |    -    | Course Introduction              |    Chapt. 1    | Physics |
| Multiplikation    |    *    | Inertia, Equilibrium, Kinematics | Chapt. 2, 3, 4 | Physics |
| Division          |    /    | Vectors, Momentum, Energy        |   Chapt. 5-8   | Physics |
| Ganzzahl Division |   //    | Vectors, Momentum, Energy        |   Chapt. 5-8   | Physics |
| Division mit Rest |    %    | Vectors, Momentum, Energy        |   Chapt. 5-8   | Physics |


: Assignment List