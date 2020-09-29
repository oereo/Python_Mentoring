## Python basic practice!

```python
x = int(input("x좌표를 입력하세요:"))
y = int(input("y좌표를 입력하세요:"))

if x > 0:
    if y > 0:
        print("1사분면")
    elif y < 0:
        print("4사분면")
    else:
        print("y축")
elif x < 0:
    if y > 0:
        print("2사분면")
    elif y < 0:
        print("3사분면")
    else:
        print("y축")
else:
    print("x축")

x = 41

if x > 20:
    print("Above ten,")
    print("and also above 20!")
elif x > 10 and x < 20:
    print("Above ten,")
    print("but not above 20.")
else:
    print("10이하")




while True:
    A , B = int(input("정수 A:")) , int(input("정수 B:"))
    if A == 0 and B == 0: 
        break
    print(A + B)
```
