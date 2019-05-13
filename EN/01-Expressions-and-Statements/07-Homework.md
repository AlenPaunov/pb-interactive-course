[slide]
# Problem: Calculate Speed
[code-task title="Calculate Speed" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function calculateSpeed (distance, time) {
   // Write your code here
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 2 numbers - distance and time
* Calculates the speed needed to travel a given distance for agiven time
* Prints the calculated result
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|15, 2|7.5| 
[/slide]

[slide]
# Solution: Calculate Speed
[code-task title="Calculate Speed" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function calculateSpeed (distance, time) {
   let speed = distance / time;
   console.log(speed);
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 2 numbers - distance and time
* Calculates the speed needed to travel a given distance for agiven time
* Prints the calculated result
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|15, 2|7.5| 
[/slide]

[slide]
# Problem: Currency Converter
[code-task title="Currency Converter" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function currencyConverter (dollars) {
   // Write your code here
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the dollars to be converted 
* Converts dollars to euro (the rate of dollars to euro is 0.88)
* Prints the converted value in euro
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|17|14.96| 
|87|76.56|
[/slide]

[slide]
# Solution: Currency Converter
[code-task title="Currency Converter" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function currencyConverter (dollars) {
   let euros = dollars * 0.88; 
   console.log(euros);
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the dollars to be converted 
* Converts dollars to euro (the rate of dollars to euro is 0.88)
* Prints the converted value in euro
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|17|14.96| 
|87|76.56|
[/slide]


[slide]
# Problem: Inches to Centimeters
[code-task title="Inches to Centimeters" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function inchesToCentimeters (inches) {
   // Write your code here
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the inches to be converted
* Calculates them to centimeters 
* Prints the result 
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|21|53.34| 
|71|180.34|
[/slide]

[slide]
# Solution: Inches to Centimeters
[code-task title="Inches to Centimeters" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function inchesToCentimeters (inches) {
   let centimeters = inches * 2.54;
   console.log(centimeters);
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the inches to be converted
* Calculates them to centimeters 
* Prints the result 
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|21|53.34 | 
|71|180.34|
[/slide]

[slide]
# Problem: Four Operations
[code-task title="Four Operations" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function fourOperations(num1, num2){
    // Write code here
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 2 parameters
* Performs the 4 arithmetic operations, in the following order: +, -, *, /
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|5, 10|5 + 10 = 15\n5 - 10 = -5\n5 * 10 = 50\n5 / 10 = 0.5| 
[/slide]

[slide]
# Solution: Four Operations
[code-task title="Four Operations" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function fourOperations (num1, num2) {
   console.log(`${num1} + ${num2} = ${num1 + num2}`);
   console.log(`${num1} - ${num2} = ${num1 - num2}`);
   console.log(`${num1} * ${num2} = ${num1 * num2}`);
   console.log(`${num1} / ${num2} = ${num1 / num2}`);
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 2 parameters
* Performs the 4 arithmetic operations, in the following order: +, -, *, /
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|5, 10|5 + 10 = 15, 5 - 10 = -5, 5 * 10 = 50, 5 / 10 = 0.5| 
[/slide]

[slide]
# Problem: Days to Minutes
[code-task title="Days to Minutes" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function daysToMinutes (days) {
   // Write your code here
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a single number (days)
* Converts the days to minutes 
* Prints the minutes
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|2|2880|
|5|7200|
[/slide]

[slide]
# Solution: Days to Minutes
[code-task title="Days to Minutes" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function daysToMinutes (days) {
   let hours = days * 24;
   let minutes = hours * 60;
   console.log(minutes);
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a single number (days)
* Converts the days to minutes 
* Prints the minutes
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|2|2880|
|5|7200|
[/slide]

[slide]
# Problem: Circle Area and Perimeter
[code-task title="Circle Area and Perimeter" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function circleArea (radius) {
   // Write your code here
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the radius of a circle
* Calculates the area and perimeter of a circle
* Prints the calculated values formatted to the 2nd decimal
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|7|Area = 153.9380400259\nPerimeter = 43.9822971502571|
[/slide]

[slide]
# Solution: Circle Area and Perimeter
[code-task title="Circle Area and Perimeter" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function circleArea (radius) {
   let area = radius * radius * Math.PI;
   let perimeter = 2 * Math.PI * radius;
   console.log(`Area = ${area.toFixed(2)}`);
   console.log(`Perimeter = ${perimeter.toFixed(2)}`);
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the radius of a circle
* Calculates the area and perimeter of a circle
* Prints the calculated values formatted to the 2nd decimal
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|7|Area = 153.9380400259\nPerimeter = 43.9822971502571|
[/slide]

[slide]
# Problem: Person Info
[code-task title="Person Info" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function personInfo (firstName, lastName, country, town) {
   // Write your code here
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 4 strings - first name, last name, country and town 
* Prints information about a person in the following format: "\{firstName\} \{lastName\} from \{country\} - \{town\}!"
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|Kelly, Smith, Ireland, Cork|Kelly Smith from Ireland - Cork!|
[/slide]

[slide]
# Solution: Person Info
[code-task title="Person Info" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function personInfo (firstName, lastName, country, town) {
   console.log(`${firstName} ${lastName} from ${country} -   ${town}!`);
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 4 strings - first name, last name, country and town 
* Prints information about a person in the following format: "\{firstName\} \{lastName\} from \{country\} - \{town\}!"
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|Kelly, Smith, Ireland, Cork|Kelly Smith from Ireland - Cork!|
[/slide]

[slide]
# Problem: Town Info
[code-task title="Town Info" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function townInfo (townName, population, area) {
  // Write your code here
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives name (string), population and area (numbers)
* Prints information about a town in the following format: "Town \{name\} has population of \{population\} and area \{area\} square km."
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|Berlin, 3675000, 984|Town Berlin has population of 3675000 and area 984 square km.|
[/slide]

[slide]
# Solution: Town Info
[code-task title="Town Info" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
function townInfo (townName, population, area) {
  console.log(`Town ${townName} has population of ${population} and area {area} square km.`);
}
```
[/code-editor]
[task-description]
Write a function, which:

* Receives name (string), population and area (numbers)
* Prints information about a town in the following format: "Town \{name\} has population of \{population\} and area \{area\} square km."
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|Berlin, 3675000, 984|Town Berlin has population of 3675000 and area 984 square km.|
[/slide]