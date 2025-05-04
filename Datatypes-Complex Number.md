# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
Add Code Here
```
# Step 1: Read an integer input for the real part
a = int(input("Enter the real part of the complex number: "))

# Step 2: Read an integer input for the imaginary part
b = int(input("Enter the imaginary part of the complex number: "))

# Step 3: Create a complex number using the complex(a, b) function
x = complex(a, b)

# Step 4: Print the complex number
print("The complex number is:", x)

# Step 5: Print the real part of the complex number
print("The real part is:", x.real)

# Step 6: Print the imaginary part of the complex number
print("The imaginary part is:", x.imag)
```

## Output
```
The complex number is: (3+4j)
The real part is: 3.0
The imaginary part is: 4.0
```
## Result
This program successfully calculates and displays the complex number as well as its real and imaginary components!
