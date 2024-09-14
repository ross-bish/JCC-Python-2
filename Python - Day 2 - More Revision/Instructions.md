# More Python Revision

![CodeWorksCodeNotWorkingGIF](https://github.com/user-attachments/assets/6b603f81-efd5-4dad-81fe-b00b7d802833)


## Problem Set A - Input and Type Conversion
### 1. Temperature Converter 🌡️
    
- Ask the user to enter a temperature in degrees `celsius` ℃.
- Convert the temperature to Fahrenheit using the formula:

    ````
     fahrenheit = (celsius * 9/5) + 32
    ````

- Store the result in a variable `fahrenheit` and print it.

- Remember to use appropriate `# comments` to explain what your code is doing.


    >
    > 

### 2. Simple Calculator 🧮

- Create a program that takes two numbers ``num1`` and ``num2`` from the user.
- Ask which operation they want to perform _**addition, subtraction, multiplication,**_ or **_division_**.
- Based on their input, perform the corresponding operation and print the result.

<details>

<summary> 👀 Hint </summary>

````python
# Add comments to explain what your code is doing.
num1 = float()
num2 = input("Enter the second number: ")
operation = input("Choose the operation (+, -, *, /): ")

if operation == "+":
    result = 

print(f"The result is: {result}")

````
  
</details>

- Remember to use appropriate `# comments` to explain what your code is doing.

## Problem Set B - Boolean and Logical Operators 
### 3. Vowel Checker

- Write a program that asks the user for a single letter and checks if it is a vowel **(a, e, i, o, u)**. 
- Print `True` if it is, otherwise print `False`.

<details>

<summary> 👀 Hint </summary>

````py

.lower()

if letter in 'aeiou':
    print()

````
</details>


### 4. Eligibility Check 🪪

- Ask the user for their ``age`` and whether they are a student (``True`` or ``False``).
- If the user is ``18`` or older and a student, print **"You qualify for the discount!"**
- Otherwise, print **"You do not qualify."**

- Remember to use appropriate `# comments` to explain what your code is doing.


## Problem Set C - Combining Concepts
### 5. Tip Calculator 💵

- Write a program that asks for the ``total bill`` amount and the ``tip percentage`` as a number **(e.g., 10 for 10%)**.
- Calculate the ``total amount`` including the tip.
- Then print the result in a _formatted string_ like **"The total bill, including a 10% tip, is $110."**

<details>
<summary> 👀Hint </summary>

````py

tip_amount = (total_bill * tip_percentage) / 100
total_amount =

# why is this formatting useful for dealing with currency?
print(f"€{total_amount: .2f}")
````
</details>



### 6. Grade Checker 📝
    
- Create a program that takes a score (0-100) from the user and prints out the corresponding grade:
````
90-100: A
80-89: B
70-79: C
60-69: D
Below 60: F
````

<details>

<summary> 👀 Hint </summary>

````py
# Get the user's grade as input
grade = int(input(""))

# Use if/elif/else statements to categorize the grade and provide a response.
if 90 <= grade <= :
    print("")
elif  <= grade <  :
    print("")
elif :
    print("")
else:
    print("")

````

  
</details>


- Remember to use appropriate `# comments` to explain what your code is doing.

## ✨Extra Credit - More If-Else and Comparison Logic
### 7. Number Range

- Ask the user for a number, and print:
  - _"The number is positive"_ if it's `>` greater than ``0``.
  - _"The number is negative"_ if it's `<` less than ``0``.
  - _"The number is zero"_ if it's `=` equal to ``0``.

### 8. Password Validator

- Write a program that checks if the user's entered ``password`` is the same as a ``predefined_password`` (stored in the code). 
- If it matches, print _"Access granted"_ otherwise print _"Access denied."_

- Remember to use appropriate `# comments` to explain what your code is doing.
