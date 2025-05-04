
# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
Add Code here
```
# Set variables based on expressions
a = 0 == True  # Evaluates to False because 0 is not equal to True
b = False == False  # Evaluates to True because False is equal to False
c = True + True  # Evaluates to 2 because True is treated as 1, so 1 + 1 = 2
d = False + 9  # Evaluates to 9 because False is treated as 0, so 0 + 9 = 9

# Print the results
print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```

## Output
```
a is False
b is True
c: 2
d: 9
```
## Result
This program successfully calculates and prints the sum of all elements in the list [1, 2, 3, 4, 5] using the built-in sum() function.
