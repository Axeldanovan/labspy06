# labspy06

# latihan 1
# Untuk latihan kali ini merubah dari fungsi ke lambda Ada 4 fungsi yang harus dirubah ke lambda
![Screenshot_5](https://user-images.githubusercontent.com/81457697/145676287-50f59153-11bc-4ed7-8973-61cb91f4d03d.png)

```python
import math


def a(x):
    return x ** 2


def b(x, y):
    return math.sqrt(x ** 2 + y ** 2)


def c(*args):
    return sum(args) / len(args)


def d(s):
    return "".join(set(s))
```

