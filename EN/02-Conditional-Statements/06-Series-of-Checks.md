[slide]
# Series of Conditions
The ***if-else*** statement can be used as a series of checks

If one condition is ***True***, the program will **NOT check** the rest of the conditions
```python
if ... : 
  # Execution code
elif ... : 
  # Execution code
elif ... :
  # Execution code
```
# Example
The program checks the first condition, finds that it is true and ends
```python
a = 7
if a > 4:
  print("Bigger than 4") 
elif a > 5:
  print("Bigger than 5") 
else 
  print("Equal to 7") 
```
[/slide]

[slide]
# Problem: Number 1...9
[code-task title="Number 1...9" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads an **integer** and checks its value \[1, 9\]
* Prints the value in the form of text
* If the number is **greater** than 9 prints ***"Number too big"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|7|even|
|10|Number too big|
[/slide]

[slide]
# Solution: Number 1...9
[code-task title="Number 1...9" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
num = int(input())
if num == 1 :
  print("one")
# TODO: Add the rest of the conditions 
else :
  print("Number too big")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads an **integer** and checks its value \[1, 9\]
* Prints the value in the form of text
* If the number is **greater** than 9 prints ***"Number too big"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|7|even|
|10|Number too big|
[/slide]