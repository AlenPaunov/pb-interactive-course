[slide]
# What is Coding?
**Coding** means to give **commands** to tell the computer what to do

Sample command:
```java
System.out.println("I am coding");
```
A **computer program** is a sequence of commands
```java
System.out.println("First command");
System.out.println("Second command");
System.out.println("Third command");
```
[/slide]

[slide]
# Commands in Java – Examples 
Calculate an expression and print its value:
```java
System.out.println(5 + 5);
```
Plays the "A" sound (works in Windows only)
```java
System.out.println("softuni".contains("uni"));
```
Print the numbers from 1 to 100
```java
for (int i = 1; i <= 100; i++) 
    System.out.println(i);
```
[/slide]

[slide]
# Programming and Algorithms 
**Programming** means writing computer programs (commands)

* Using certain **programming language**, such as C# or Python

**Algorithm** == a sequence of commands that achieves certain result

Programming is done by **programmers** (developers)

Programmers use IDE (like IntelliJ IDEA) to:

* **Write** the code
* **Run** and test the code
* Find a fix **bugs** (debug the code)
[/slide]

[slide]
# Computer Program – Example
Sample C# program (sequence of C# commands):

```java
int size = 5;
System.out.println("Size = " + size);
System.out.println("Area = " + size * size);
```

[image src="https://github.com/tany1610/programming-basics-interactive-java/blob/master/assets/intro-to-programming-1.png"/]
[/slide]

[slide]
# Complete Computer Program
Sample complete C# program (class + method + commands):
```java
using System;

class SquareArea
{
  public static void Main()
  {
    var size = 5;
    Console.WriteLine("Size = " + size);
    Console.WriteLine("Area = " + size * size);
  }
}
```
[/slide]

[slide]
# Console-Based C# Program – Example
C# program, which converts from USD to EUR

```java
using System;

class SquareArea
{
  public static void Main()
  {
    var dollars = int.Parse(Console.ReadLine());
    var euro = dollars * 0.883795087;
    Console.WriteLine("Euro: " + euro);
  }
}
```
[/slide]