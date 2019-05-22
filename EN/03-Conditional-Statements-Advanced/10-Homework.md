[slide]
# Homework
Now, it's your turn to practice what you have learned in the training session.

We have prepared some simple problems for you to solve. If you struggle you can see the solution after each problem. 
[/slide]

[slide]
# Problem: Fruit or Vegetable
[code-task title="Fruit or Vegetable" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a single input line: "fruit" or "vegetable"
    * Fruits: banana, apple, kiwi, cherry, lemon, grapes
    * Vegetables: cucumber, pepper, carrot
* Prints: "vegetable", "fruit" or "unknown"
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|lemon|fruit|
|carrot|vegetable|
[/slide]

[slide]
# Solution: Fruit or Vegetable
[code-task title="Fruit or Vegetable" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
product = input()
if product == "cucumber":
  print("vegetable")
elif product == "pepper":
  print("vegetable")
elif product == "carrot":
  print("vegetable")
elif product == "apple":
  print("fruit")
elif product == "kiwi":
  print("fruit")
elif product == "cherry":
  print("fruit")
elif product == "lemon":
  print("fruit")
elif product == "grapes":
  print("fruit")
else:
  print("unknown")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a single input line: "fruit" or "vegetable"
    * Fruits: banana, apple, kiwi, cherry, lemon, grapes
    * Vegetables: cucumber, pepper, carrot
* Prints: "vegetable", "fruit" or "unknown"
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|lemon|fruit|
|carrot|vegetable|
[/slide]

[slide]
# Problem: Day of Week
[code-task title="Day of Week" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads n integer representing the day of the week in range \[1..7\]
* Prints the name of the day
* Prints "Error" if the number is not in the given range print
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|Monday|
|9|Error|
[/slide]

[slide]
# Solution: Day of Week
[code-task title="Day of Week" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
day = int(input())
if day == 1:
  print("Monday")
elif day == 2:
  print("Tuesday") 
elif day == 3:
  print("Wednesday")
elif day == 4:
  print("Thursday")
elif day == 5:
  print("Friday")
elif day == 6:
  print("Saturday")
elif day == 7:
  print("Sunday")
else: 
  print("Error")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads n integer representing the day of the week in range \[1..7\]
* Prints the name of the day
* Prints "Error" if the number is not in the given range print
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|Monday|
|9|Error|
[/slide]

[slide]
# Problem: Product of 3 Numbers
[code-task title="Product of 3 Numbers" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 3 real numbers
* Prints the product of 3 numbers (positive, negative or zero)
* Try to do this WITHOUT multiplying the 3 numbers
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2|negative|
|3||
|-1||

|Input|Output|
|-----|------|
|-3|positive|
|-4||
|5||
[/slide]

[slide]
# Solution: Product of 3 Numbers
[code-task title="Product of 3 Numbers" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
n1 = int(input())
n2 = int(input())
n3 = int(input())
if n1 == 0 or n2 == 0 or n3 == 0:
  print("zero")
else:
  negative_numbers = 0
  if n1 < 0: negative_numbers += 1
  if n2 < 0: negative_numbers += 1
  if n3 < 0: negative_numbers += 1
  if negative_numbers % 2 == 0:
    print("positive")
  else
    print("negative")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 3 real numbers
* Prints the product of 3 numbers (positive, negative or zero)
* Try to do this WITHOUT multiplying the 3 numbers
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2|negative|
|3||
|-1||

|Input|Output|
|-----|------|
|-3|positive|
|-4||
|5||
[/slide]

[slide]
# Problem: Sorted Numbers
[code-task title="Sorted Numbers" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 3 real numbers
* Prints "Ascending" If numbers are sorted in ascending order
* Prints "Descending" if numbers are sorted in descending order
* Prints "Not sorted" in any other case
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|Ascending|
|2||
|3||

|Input|Output|
|-----|------|
|3|Not sorted|
|1||
|2||
[/slide]

[slide]
# Solution: Sorted Numbers
[code-task title="Sorted Numbers" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
n1 = float(input())
n2 = float(input())
n3 = float(input())
if n1 > n2 and n2 > n3:
  print("Descending")
elif n1 < n2 and n2 < n3:
  print("Ascending")
else
  print("Not sorted")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 3 real numbers
* Prints "Ascending" If numbers are sorted in ascending order
* Prints "Descending" if numbers are sorted in descending order
* Prints "Not sorted" in any other case
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|Ascending|
|2||
|3||

|Input|Output|
|-----|------|
|3|Not sorted|
|1||
|2||
[/slide]

[slide]
# Problem: Vacation Expenses
[code-task title="Vacation Expenses" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads season, accommodation type and count of the days
* Prints the total expenses, formatted to the 2nd digit after the decimal point
|Season|Hotel|Camping|Discount|
|------|-----|-------|--------|
|Spring|30|10|20%|
|Summer|50|30|0%|
|Autumn|20|15|30%|
|Winter|40|10|10%|
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Solution: Vacation Expenses
[code-task title="Vacation Expenses" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
season = input()
accommodation = input()
days = int(input()) 
if season == "Spring":
  if accommodation == "Hotel":
    totalPrice = days * 30 * 0.80
  elif accommodation == "Camping":
    totalPrice = days * 10 * 0.80
elif season == "Summer":
  if accommodation == "Hotel":
    totalPrice = days * 50
  elif accommodation == "Camping":
    totalPrice = days * 30 
elif season == "Autumn":
  if accommodation == "Hotel":
    totalPrice = days * 20 * 0.7
  elif accommodation == "Camping":
    totalPrice = days * 15 * 0.7
elif season == "Winter":
  if accommodation == "Hotel":
    totalPrice = days * 40 * 0.9
  elif accommodation == "Camping":
    totalPrice = days * 10 * 0.9
```
[/code-editor]
[task-description]
Write a program, which:

* Reads season, accommodation type and count of the days
* Prints the total expenses, formatted to the 2nd digit after the decimal point
|Season|Hotel|Camping|Discount|
|------|-----|-------|--------|
|Spring|30|10|20%|
|Summer|50|30|0%|
|Autumn|20|15|30%|
|Winter|40|10|10%|
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Problem: Cinema
[code-task title="Cinema" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads the type of the movie, the rows and the seats per row in the cinema
* Prints the total income formatted to the 2nd digit after the decimal point

|Type|Price|
|----|-----|
|Premiere|12.00|
|Normal|7.50|
|Discount|5.00|
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Solution: Cinema
[code-task title="Cinema" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
type = input()
rows = int(input())
cols = int(input())
totalSeats = rows * cols
if type == "Premiere":
  print(f"{totalSeats * 12.0:.2f}")
elif type == "Normal":
  print(f"{totalSeats * 7.50:.2f}")
elif type == "Discount":
  print(f"{totalSeats * 5.00:.2f}")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads the type of the movie, the rows and the seats per row in the cinema
* Prints the total income formatted to the 2nd digit after the decimal point

|Type|Price|
|----|-----|
|Premiere|12.00|
|Normal|7.50|
|Discount|5.00|
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Problem: Number Operations
[code-task title="Number Operations" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads two real numbers and math operator from the console
* The math operator could be: "+", "-", "/", "%" and "\*"
* The output should be in the following format: "\{N1\} \{operator\} \{N2\} = \{result\}"
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|10|10 + 12 = 22|
|12||
|+||
[/slide]

[slide]
# Solution: Number Operations
[code-task title="Number Operations" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
num1 = float(input())
num2 = float(input())
operation = input()
result = 0
if operation == "+":
  result = num1 + num2
elif operation == "-":
  result = num1 - num2
elif operation == "/":
  result = num1 / num2
elif operation == "*":
  result = num1 * num2
print(f"{num1} {operation} {num2} = {result}")  
```
[/code-editor]
[task-description]
Write a program, which:

* Reads two real numbers and math operator from the console
* The math operator could be: "+", "-", "/", "%" and "\*"
* The output should be in the following format: "\{N1\} \{operator\} \{N2\} = \{result\}"
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|10|10 + 12 = 22|
|12||
|+||
[/slide]

[slide]
# Problem: ATM
[code-task title="ATM" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads: balance, withdraw and limit
* Prints "The withdraw was successful." if the balance is enough, "The daily limit was exceeded." if the limit is exceeded and "Insufficient availability." if the balance isn't enough
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|420|The withdraw was successful|
|20||
|25||
[/slide]

[slide]
# Solution: ATM
[code-task title="ATM" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
balance = float(input())
withdraw = float(input())
limit = float(input())
if balance >= withdraw and withdraw <= limit:
  print("The withdraw was successful.")
elif withdraw > dailyLimit:
  print("The daily limit was exceeded.") 
elif withdraw > balance:
  print("Insufficient availability.")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads: balance, withdraw and limit
* Prints "The withdraw was successful." if the balance is enough, "The daily limit was exceeded." if the limit is exceeded and "Insufficient availability." if the balance isn't enough
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|420|The withdraw was successful|
|20||
|25||
[/slide]

[slide]
# Problem: Five Numbers
[code-task title="Five Numbers" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 5 integers
* Prints the biggest number
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|5|
|2||
|3||
|4||
|5||
[/slide]

[slide]
# Solution: Five Numbers
[code-task title="Five Numbers" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
num1 = int(input())
num2 = int(input())
num3 = int(input())
num4 = int(input())
num5 = int(input())
if num1 > num2 and num1 > num3 and num1 > num4 and num1 > num5:
  print(num1)
elif num2 > num1 and num2 > num3 and num2 > num4 and num2 > num5:
  print(num2)
elif num3 > num1 and num3 > num2 and num3 > num4 and num3 > num5:
  print(num3)
elif num4 > num1 and num4 > num2 and num4 > num3 and num4 > num5:
  print(num4)
elif num5 > num1 and num5 > num2 and num5 > num3 and num5 > num4:
  print(num5)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 5 integers
* Prints the biggest number
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|5|
|2||
|3||
|4||
|5||
[/slide]

[slide]
# Problem: Biggest Character
[code-task title="Biggest Character" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 3 characters on separate lines
* Prints the character with the biggest ASCII value
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|a|c|
|b||
|c||
[/slide]

[slide]
# Solution: Biggest Character
[code-task title="Biggest Character" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
first_char = input()
second_char = input()
third_char = input()
if ord(first_char) > ord(second_char) and ord(first_char) > ord(third_char):
    print(first_char)
elif ord(second_char) > ord(first_char) and ord(second_char) > ord(third_char):
    print(second_char)
else:
  print(third_char)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 3 characters on separate lines
* Prints the character with the biggest ASCII value
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|a|c|
|b||
|c||
[/slide]