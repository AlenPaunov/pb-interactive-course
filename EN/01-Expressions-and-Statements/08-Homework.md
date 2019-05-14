[slide]
# Problem: Area of Triangle
[code-task title="Area of Triangle" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```
// Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads from input, a side - a and height for that side - ha
* Calculates the area of a triangle
* Prints the area, formatted to the 2nd digit after decimal point
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5, 10|25.00|
[/slide]

[slide]
# Solution: Area of Triangle
[code-task title="Area of Triangle" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```
double a = Double.parseDouble(scanner.nextLine());
double h = Double.parseDouble(scanner.nextLine());
double area = (a * h) / 2;
System.out.printf("%.2f", area);
```
[/code-editor]
[task-description]
Write a program, which:

* Reads from input, a side - a and height for that side - ha
* Calculates the area of a triangle
* Prints the area, formatted to the 2nd digit after decimal point
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5, 10|25.00|
[/slide]
