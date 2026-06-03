# 1. Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```py
a=16
print(bin(a))
```

## Output
<img width="1632" height="190" alt="image" src="https://github.com/user-attachments/assets/faa0ddca-c2bb-4e3f-8856-65a64321158e" />

## Result
Successfully wrote a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

# 2. Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```py
def result(a,b):
    return a%b
print("Reminder is",result(int(input("Enter numerator:")),int(input("Enter Denominator:"))))
```
## Output
<img width="866" height="168" alt="image" src="https://github.com/user-attachments/assets/d6adbfa7-595a-437b-88c9-6be30e8f25a9" />

## Result
Successfully wrote a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

# 3.Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```py
add=lambda a,b: a+b
print("Sum of given is",add(int(input("Enter any number")),int(input('Enter any number'))))
```

## Output
<img width="841" height="142" alt="image" src="https://github.com/user-attachments/assets/3030ef12-f6d8-41a6-8eaf-7249e9134569" />

## Result
Successfully wrote a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.


# 4. Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```py
import math
rows=int(input())
for n in range(rows):
        print(" " * (rows - n), end=" ")
        for k in range(n + 1):
            # Compute C(n, k) = n! / (k! * (n-k)!)
            value = math.comb(n, k)
            print(value, end=" ")
        print()
```

## Sample Output
<img width="583" height="392" alt="image" src="https://github.com/user-attachments/assets/3173646d-7aa0-40f6-b8b7-5f9d86d9ff6c" />

## Result
Successfully wrote a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

# 5. Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```py
num = int(input("Enter a number: "))
temp = num
rev = 0
while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10
if rev == num:
    print("The number is a palindrome.")
else:
    print("The number is not a palindrome.")
```
## Output
<img width="436" height="292" alt="image" src="https://github.com/user-attachments/assets/df14742e-bded-4ef7-b266-bebb4ef81f8a" />
<img width="427" height="287" alt="image" src="https://github.com/user-attachments/assets/0a511faf-596f-4f52-88c8-6da134f12811" />

## Result
Successfully wrote a Python program that checks whether a given number is a **palindrome** using loops.
