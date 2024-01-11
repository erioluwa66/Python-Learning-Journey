Day 2: Data Types and Basic Operations
Table of Contents
String
Integer and Float
Boolean
Arithmetic Operations
PEDMAS
Input and Type Conversion
BMI Calculation
F-String and Variables
Life Expectancy

String
Accessing an individual character in a string and concatenation.
print("Hello"[4])
print("123" + "345")

Integer and Float
Basic arithmetic operations with integers and floats.
print(123 + 345)
print(3.1459)

Boolean
Boolean data type with examples.
True
False

Arithmetic Operations
Basic arithmetic operations in Python.
3 + 5
7 - 4
3 * 2
6 / 3
2 ** 3

PEDMAS
Order of operations using parentheses, exponents, multiplication, division, addition, and subtraction.
(3 * (3 + 3) / 3 - 3)
print(round(8/3, 2))

Input and Type Conversion
Taking user input and performing type conversion.
two_digit_number = input()
print(type(two_digit_number))
first_digit = int(two_digit_number[0])
second_digit = int(two_digit_number[1])
print(first_digit + second_digit)

BMI Calculation
Calculating BMI using user input.
height = input()
weight = input()
weight_as_int = int(weight)
height_as_float = float(height)
bmi = weight_as_int / height_as_float ** 2
bmi_as_int = int(bmi)
print(bmi_as_int)

F-String and Variables
Using f-strings and variables.
score = 0
height = 1.8
isWinning = True
print(f"Your score is {score}, your height is {height}, you are winning is {isWinning}")

Life Expectancy
Calculating weeks left based on user input.
age = input()
years = 90 - int(age)
weeks = years * 52
print(f"You have {weeks} weeks left.")