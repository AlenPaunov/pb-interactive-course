[slide]
# What is Console(Terminal)?
* The system **console** / **terminal** / **standard input and output**
  * A special window, used to communicate with the user
  * Using a text-based input / output (command line interface)
  * Displays text data (text lines)
  * Reads user input (text lines)

[image src="https://github.com/AlenPaunov/pb-interactive-course/blob/01-expressions-and-statements/assets/expressions-and-statements-1.png"/]

[/slide]

[slide]

# Reading User Input
* Everything we read from the console comes as a **string**
* Reading user input from the console:
```csharp
string name = Console.ReadLine();
```
* Everything we print on the console is converted to **string**
```csharp
Console.WriteLine("Hello world!");
```
```csharp
Console.WriteLine(123);
```
```csharp
Console.WriteLine("Hello" + 123);
```

[/slide]

[slide]

# Formatting Output
* Formatting text with **placeholders**
```csharp
string firstName = "John";
string lastName = "Doe";
Console.WriteLine("{0} {1}", firstName, lastName);
// John Doe
```
* Formatting numbers with **placeholders**
```csharp
double a = 5.123;
double b = 6.456;
Console.WriteLine("{0:F2}", a + b); // 11.58
```
* Formatting output using **string interpolation**
  * The '**$**' syntax turns on the expression calculation
  * **Parameters** are put directly in **placeholders**
```csharp
int day = 12;
string month = "April";
int year = 2018
Console.WriteLine($"{day}-{month}-{year}");
// 12-April-2018
```
[/slide]

[slide]

# Reading User Input
* A program which **reads** a name from the console and **prints** it:
```csharp
string name = Console.ReadLine();
Console.WriteLine(name);
```
* The result from the execution would be:

[image src="https://github.com/AlenPaunov/pb-interactive-course/blob/01-expressions-and-statements/assets/expressions-and-statements-2.png"/]

[/slide]

[slide]

# Reading Integers
* Reading an integer number:
```csharp
int num = int.Parse(Console.ReadLine());
```
* Example: 
  * Calculating square's area by given side **a**
  ```csharp
  int a = int.Parse(Console.ReadLine());
  int area = a * a;
  Console.WriteLine(area);
  ```

[/slide]

[slide]

# Reading Floating-Point Numbers

[/slide]