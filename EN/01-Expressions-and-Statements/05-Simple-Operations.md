[slide]
# Problem: Greeting
[code-task title="Greeting" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a user input - name, from the console
* Prints "Hello, \{name\}!", where \{name\} is the user input
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|John|Hello, John|
|Dave|Hello, Dave|
[/slide]

[slide]
# Solution: Greeting
[code-task title="Greeting" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
name = input()
print('Hello', end=" ")
print(name)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a user input - name, from the console
* Prints "Hello, \{name\}!", where \{name\} is the user input
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|John|Hello, John|
|Dave|Hello, Dave|
[/slide]

[slide]
# Concatenating Text and Numbers
Examples:

```python
first_name = "John"
last_name = "Doe"
age = 34
text = first_name + " " + last_name + " | " + str(age)
print(text) # John Doe | 34
```
```python
a = 5
b = 11
print(f'a + b = {a + b}')
# a + b = 511
``` 
[/slide]

[slide]
# Arithmetic Operators
Adding numbers (operator **+**)
```python
a = 5
b = 7
sum = a + b
print(sum) # 12
```
Subtracting numbers (operator **-**)
```python
a = 15
b = 7
print(a - b) # 8
```
Multiplying numbers (operator **\***)
```python
a = 5
b = 7
print(a * b) # 35
```
Dividing numbers (operator **\/** )
```python
a = 25
b = 4
print(a / b) # 6.25
```
Modulo / remainder from integer division (operator **%**)
```python
print(3 % 2) # 1
print(4 % 2) # 0
print(3.5 % 1) # 0.5
```
[/slide]