# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

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
def factorial(n):

if n == 0 or n == 1:
    return 1
return n * factorial(n - 1)
def combination(n, k):

return factorial(n) // (factorial(k) * factorial(n - k))
num_rows = int(input("Enter number of rows: "))

for i in range(num_rows):

print(' ' * (num_rows - i - 1), end='')
for j in range(i + 1):
    print(combination(i, j), end=' ')
print()
Add Code Here

## Sample Output
![WhatsApp Image 2026-03-27 at 12 25 18 AM](https://github.com/user-attachments/assets/efcc0a56-06e8-455d-91a4-5bad8fe363ac)


## Result
Thus the prgram has been successfully executed

