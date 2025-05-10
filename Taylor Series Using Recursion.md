# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:
```
def sum_digit(n):
    if n <= 0:
        return 0
    return n % 10 + sum_digit(n // 10)

num = int(input("Enter a number: "))
result = sum_digit(num)
print("Sum of digits:", result)
```

## OUTPUT
![image](https://github.com/user-attachments/assets/f6148915-1235-48b8-b1e8-81b8ccd672b5)

## RESULT
Thus,the program is executed successfully

