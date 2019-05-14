[slide]
# Arithmetic Operators
There are several arithmetic operators:

* "+" - addition
* "-" - subtraction
* "*" - multiplication
* "/" - division
* "%" - modulus
* "++" - increment
* "--" - decrement 
[/slide]

[slide]
# Assignment Operators
There are several assignment operators:

* "=" 
* "+=" 
* "-=" 
* "*="
* "/=" 
* "%="

```js
let a = 2;   // 2
a += 3;      // 5
a -= 1;      // 4
a *= 3;      // 12
a /= 2;      // 6
```
[/slide]

[slide]
# Problem: Area of Triangle
[code-task title="Area of Triangle" executionStrategy="javascript-code" requiresInput]
[code-editor language=javascript]
```
function printTriangleArea(a, h) {
    // Write your code here
}
```
[/code-editor]
[task-description]
Create a function that receives two numbers:

* The side of a triangle - a
* The height for that side - ha
* Print the area formatted to the 2nd digit
* Hint: use the "toFixed" method for formatting
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
[code-task title="Area of Triangle" executionStrategy="javascript-code" requiresInput]
[code-editor language=javascript]
```
function printTriangleArea(a, h) {
   let area = (a * h) / 2;
   console.log(area.toFixed(2));
}
```
[/code-editor]
[task-description]
Create a function that receives two numbers:

* The side of a triangle - a
* The height for that side - ha
* Print the area formatted to the 2nd digit
* Hint: use the "toFixed" method for formatting
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5, 10|25.00|
[/slide]
