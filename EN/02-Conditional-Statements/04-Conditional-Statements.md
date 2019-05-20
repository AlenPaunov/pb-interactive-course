[slide]
# Simple Conditions
Often we have to check certain conditions and take action according to the result

```python
if condition: 
  # Code for execution
  # if the condition is true
```

The result is either ***True*** or ***False***
[/slide]

[slide]
# Indentation
Leading whitespace is used to compute the indentation level of the line, which is used to determine the grouping of statements.
```python
   name = "John"
if name == "John": 
  print(name)
# Indentation Error
```
```python
name = "John"
if name == "John": 
  print(name)  #John
# Correct Indentation
```
[/slide]

[slide]
# Problem: Freezing Weather
[code-task title="Freezing Weather" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a temperature in Celsius
* **Checks** whether the temperature is **below zero**
* Prints ***"Freezing weather!"***, if the temperature is equal or lower than 0, otherwise print ***"No output"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|(No output)|
|-2|Freezing weather!|
[/slide]

[slide]
# Solution: Freezing Weather
[code-task title="Freezing Weather" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
temperature = float(input())
if temperature <= 0
   print("Freezing weather!")
else
   print("No output")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a temperature in Celsius
* **Checks** whether the temperature is **below zero**
* Prints ***"Freezing weather!"***, if the temperature is equal or lower than 0, otherwise print ***"No output"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|(No output)|
|-2|Freezing weather!|
[/slide]