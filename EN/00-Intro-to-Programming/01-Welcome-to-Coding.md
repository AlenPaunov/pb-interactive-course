[slide]
# What is Coding?
**Coding** means to give **commands** to tell the computer what to do

Sample command:
```js
console.log("I am coding");
```
A **computer program** is a sequence of commands
```js
console.log("First command");
console.log("Second command");
console.log("Third command");
```
[/slide]

[slide]
# Running JavaScript Commands
The easiest way to run JavaScript commands (JS commands)

The browser console: press \[F12\] in your Web browser

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

```js
int size = 5;
System.out.println("Size = " + size);
System.out.println("Area = " + size * size);
```

[image src="https://github.com/AlenPaunov/pb-interactive-course/blob/00-js-intro-to-programming/assets/intro-to-programming-1.png"/]
[/slide]

[slide]
# Complete Computer Program
Sample complete js program (class + method + commands):
```js
public class Main {
  public static void main(String[] args) {
    int size = 5;
    System.out.println("Size = " + size);
    System.out.println(
      "Area = " + size * size);
  }
}
```
[/slide]

[slide]
# Console-Based js Program – Example
C# program, which converts from **USD** to **EUR**
```js
using System;

class Program
{
  public static void Main()
  {
    Scanner scanner = new Scanner(System.in);
    int dollars = scanner.nextInt();
    double euro = dollars * 0.883795087;
    System.out.print("Euro: " + euro);
  }
}
```
[/slide]