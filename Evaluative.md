```
coefficients = list(map(int,input().split()))
x = int(input())

r = 0
for coff in reversed(coefficients):
    r = r*x + coff

print(r)
```
