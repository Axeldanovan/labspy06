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

# Dirubah menggunakan Lambda

```python
aa = lambda x: x ** 2
bb = lambda x, y: math.sqrt(x ** 2 + y ** 2)
cc = lambda *args: sum(args) / len(args)
dd = lambda s: "".join(set(s))
```

# Penjelasan
-Untuk memperluas daftar fungsi matematika gunakan import math
-Fungsi lambda yang menggunakan variabel a-d

```python
def a(x):
    return x**2
    a = lambda x : x ** 2
print(a(2))

def b(x, y):
    return math.sqrt(x**2 + y**2)
    b = lambda x, y : x ** 2  + y ** 2
print(b(2, 2))

def c(*args):
    return sum(args)/len(args)
    c = lambda *args : sum(args)/len(args)
print(c(5, -1, 8, 19))

def d(s):
    return "".join(set(s))
    d = lambda s: "".join(set(s))
print(d("Jenab"))
```
