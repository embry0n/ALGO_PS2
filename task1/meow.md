# Простое решение

```sh
a, b = map(int, input().split(' '))


if b > a:
    min1 = b // 2
    max1 = a // 1 

elif a>b:
    min1 = a // 2
    max1 = b // 1
    
print(min1, max1)
```

# Супер умное решение 

```sh
a, b = map(int, input().split())

min_flamingos = (b + 1) // 2
max_flamingos = a

print(min_flamingos, max_flamingos)
```
