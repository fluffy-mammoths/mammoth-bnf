# Backus–Naur form for Mammoth programming language

```
def addTwo(x: Int): Int =
  return x + 2

def subtractOne(x: Int): Int =
  return x - 1

def divideByThree(x: Int): Int =
  return x / 3

def multiplyByFour(x: Int): Int =
  return x * 4

def main() =
  let x be 7
  multiplyByFour(subtractOne(divideByThree(addTwo(x))))
```
