[slide]
# Simple Conditions - if-else
If the condition is ***False***, we may execute another code - using the statement ***еlse*** 
```python
if ... :
   # Condition is true
else:
   # Condition is false
```
# Example
```python
color = "red"
if color == "red":
   print("tomato")
   print("strawberry") 
else:
   print("banana")
   print("lemon")
```
[/slide]

[slide]
# Problem: Even or Odd
[code-task title="Even or Odd" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which: 

* Checks whether a number is **even** or **odd**
* If it's **even**, it should print ***"even"***
* If it's **odd**, it should print ***"odd"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|even|
|7|odd|
[/slide]

[slide]
# Solution: Even or Odd
[code-task title="Even or Odd" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
num = int(input())
if num % 2 == 0: 
   print("even")
else:
   print("odd")
```
[/code-editor]
[task-description]
Write a program, which: 

* Checks whether a number is **even** or **odd**
* If it's **even**, it should print ***"even"***
* If it's **odd**, it should print ***"odd"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|even|
|7|odd|
[/slide]