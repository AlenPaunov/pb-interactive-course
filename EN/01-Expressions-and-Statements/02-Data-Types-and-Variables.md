[slide]
# Data Types and Variables
**Data type** - Classification that specifies which type of value a variable has

**Variables** - A characteristic that takes different values in different situations
```js
// variable  data type
let number = 5; // Number
```
[/slide]

[slide]
# Assigning Values to Variables
You can assign value to a variable and use it later

Use "**=**" to assign a value

```js
let firstNum = 10;
let secondNum = 5;
firstNum + secondNum   // 15
```
[/slide]

[slide]
# Data Types
Six data types that are primitives:

* Boolean         
* Null                
* Undefined    
* Number        
* String            
* Symbol (new in ECMAScript 6)
[/slide]

[slide]
# Data Types are Dynamic
In JavaScript data types are dynamic

A single variable can be used to hold different data types

```js
let x = 5;   // x is Number
x = "John";  // x is String
x = true;  // x is Boolean
```
[/slide]

[slide]
# String Interpolation
You can insert a variable in a string using the following syntax:

```js
let name = "John"; 
console.log(`Hi, ${name}`);
```
[/slide]

[slide]
# Log Variables on the Console
Use the "**console.log**" function

```js
let firstNum = 10;
let secondNum = 5;
console.log(firstNum + secondNum); // 15
```
[/slide]

[slide]
# Read User Input
Use functions

```js
function printNum (number) {
   console.log(number);
}
```

Call the function by name

```js
printNum(5);  // 5
printNum(10); //10
```

[/slide]

[slide]
# Passing Multiple Parameters
You can pass multiple parameters to a function

```js
function printSum (firstNum, secondNum) {
   console.log(firstNum, secondNum);
}

printSum(5, 10);       // 15
console.log(firstNum); // undefined
```

[/slide]

[slide]
# Problem: Greeting
[code-task title="Greeting" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function sayHello (user) {
   // Write your code here
}
```
[/code-editor]
[task-description]
Create a function that:

* Receives a name
* Prints "Hello, {name}" on the console
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Solution: Greeting
[code-task title="Greeting" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function sayHello (user) {
   console.log(`Hello, ${user}`);
}
```
[/code-editor]
[task-description]
Create a function that:

* Receives a name
* Prints "Hello, {name}" on the console
[/task-description]
[code-io /]
[/code-task]
[/slide]

