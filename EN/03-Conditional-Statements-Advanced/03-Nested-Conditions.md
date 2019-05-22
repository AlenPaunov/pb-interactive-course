[slide]
# Nested Conditions
An ***if...else*** statement can exist within another ***if...else*** statement

Generally used when we have to test one condition followed by another

It's not a good practice to exceed **three nested levels**

Only if the first condition is true the nested one is checked
```python
if expression:
  if nested expression:
    # Code to be executed
  else:
    # Code to be executed
# Executes when the nested expression is false
```
[/slide]

[slide]
# Problem: Marketplace
[code-task title="Marketplace" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Read a product and day from the console

Print the price, formatted to 2nd digit, based on the price list:

|Product|Weekday|Weekend|
|-------|-------|-------|
|Banana|2.50|2.70|
|Apple|1.30|1.60|
|Kiwi|2.20|3.00|
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|Banana|2.50|
|Weekday||
[/slide]

[slide]
# Solution: Marketplace
[code-task title="Marketplace" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
if product == "Banana":
  if day_of_week == "Weekday":
    print("2.50")
  else:
    print("2.70")
elif product == "Apple":
  if day_of_week == "Weekday":
    print("1.30")
  else:
    print("1.60")
elif product == "Kiwi":
  if day_of_week == "Weekday":
    print("2.20")
  else:
    print("3.00")
```
[/code-editor]
[task-description]
Read a product and day from the console

Print the price, formatted to 2nd digit, based on the price list:

|Product|Weekday|Weekend|
|-------|-------|-------|
|Banana|2.50|2.70|
|Apple|1.30|1.60|
|Kiwi|2.20|3.00|
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|Banana|2.50|
|Weekday||
[/slide]

[slide]
# Problem: Biggest Number of Three
[code-task title="Biggest Number of Three" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads three numbers from the console
* Prints the biggest number
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|3|
|2||
|3||

|Input|Output|
|-----|------|
|-1|-1|
|-5||
|-9||
[/slide]

[slide]
# Solution: Biggest Number of Three
[code-task title="Biggest Number of Three" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
first = float(input())
second = float(input())
third = float(input())
if first > second:
  if first > third:
    print(first)
  else:
    print(third)
else:
  if second > third:
    print(second)
  else:
    print(third)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads three numbers from the console
* Prints the biggest number
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|3|
|2||
|3||

|Input|Output|
|-----|------|
|-1|-1|
|-5||
|-9||
[/slide]