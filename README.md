# xu

The `xu` module exports the following functions:

    bool
    bool_list
    bool_matrix
    char
    char_list
    char_matrix
    int
    int_list
    int_matrix
    number
    number_list
    number_matrix
    random
    random_list
    random_matrix
    range
    range_list
    range_matrix
    str
    str_list
    str_matrix
    uniform
    uniform_list
    uniform_matrix

> This module uses a `random.SystemRandom` instance to operate.

## Examples

```python
import xu

for it in xu.str_list(8, 8):
    print(it)
```

    nuG37EKl
    838W1466
    07v5ve1s
    rwvI17W3
    488pnBHV
    T63Fk4hM
    FJO7Q1H0
    uW4i2SY2

* * *

```python
import xu

for row in xu.int_matrix(4, 9):
    print(row)
```

    [4, 8, 4, 8]
    [3, 2, 6, 2]
    [3, 1, 5, 2]
    [8, 1, 1, 2]
