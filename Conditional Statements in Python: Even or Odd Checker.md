# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```python
a=int(input())
if(a%2==0 and a<=30):
    print(f"{a} is an Even number")
    print(f"{a} is lesser than or equal to 30")
else:
  print(f"{a} is NOT an Even number")
```
## Output
<img width="710" height="294" alt="image" src="https://github.com/user-attachments/assets/c5bc8860-2b48-4cbc-9c60-ef7da143acbf" />


## Result
Thus the python program for to check whether the given number is **even** or **odd** using `if...else` statements has verified successfully
