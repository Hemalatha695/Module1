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
```
# Step 1: Get input from the user
user_input = input("Enter a number: ")

# Step 2: Convert input to an integer
a = int(user_input)

# Step 3: Check if the number is even or odd
if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```
## Output
```
Enter a number: 4
EVEN
```

## Result
The program successfully calculates and prints the sum of all elements in the list using the built-in sum() function.
