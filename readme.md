a = 0
b = 1
fnumbers = [1]
for i in range(2, 11):
    c = a + b
    a = b
    b = c
    fnumbers.append(b)
print("Fibonacci numbers: ", fnumbers)
