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
```
a = (0 == True)
b = (False== False)
c = True + True
d = False + 9
print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```
## Output
![Screenshot 2025-04-29 214339](https://github.com/user-attachments/assets/1ac29842-01b5-422f-9b45-bd9a7a7fe71d)

## Result
Thus the program has been successfully executed
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
a=int (input ()) 
if(a%2) == 0:
print("EVEN")
else:
print("ODD")
```
## Output
![Screenshot 2025-04-29 214033](https://github.com/user-attachments/assets/498734ad-de34-4e81-821d-2d26304975c8)

## Result
Thus the program has been successfully executed
# Datatypes-Character Literal in Python


## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
print('T')
print('a')
```
## Output
![Screenshot 2025-04-29 214712](https://github.com/user-attachments/assets/65f96a87-e98c-4e6f-aff9-bc2cacd2b2a2)

## Result
Thus, the program has been successfully executed.
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
```
a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)
```

## Output
![Screenshot 2025-04-29 214420](https://github.com/user-attachments/assets/ce9c624d-cfb4-489d-8c21-08c580d475b3)

## Result
Thus, the program has been successfully executed.
# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon=input()
print(men_stepped_on_the_moon)
```
## Output
![Screenshot 2025-04-29 214508](https://github.com/user-attachments/assets/904b3e9b-fc38-486a-afcd-e924b13469a4)

## Result
Thus, the program has been successfully executed.
