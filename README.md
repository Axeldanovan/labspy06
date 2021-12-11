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
```python
print("Latihan a")
print("=========")
print("Fungsi\t = ", (a(4)))
print("Lambda\t = ", (aa(4)))
print()
print("Latihan b")
print("=========")
print("Fungsi\t = ", (b(4, 7)))
print("Lambda\t = ", (bb(4, 7)))
print()
print("Latihan c")
print("=========")
print("Fungsi\t = ", (c(10)))
print("Lambda\t = ", (cc(10)))
print()
print("Latihan d")
print("=========")
print("Fungsi\t = ", (d("abcde")))
print("Lambda\t = ", (dd("abcde")))
```
