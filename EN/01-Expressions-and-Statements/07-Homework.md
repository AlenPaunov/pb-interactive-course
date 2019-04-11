[slide]
# Problem: Calculate Speed
[code-task title="Calculate Speed" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      // Write code here
    }
}
```
[/code-editor]
[task-description]
* Write a program to calculate the speed by time and distance:
  * Read 2 floating-point numbers: distance and time
  * Calculate the speed needed to travel a given distance for given time
  * Print the calculated result
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|15<br>2|7.5  | 
[/slide]

[slide]
# Solution: Calculate Speed
[code-task title="Calculate Speed" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      double distance = double.Parse(Console.ReadLine());
      double time = double.Parse(Console.ReadLine());
      double speed = distance / time;
      Console.WriteLine(speed);
    }
}
```
[/code-editor]
[task-description]
* Write a program to calculate the speed by time and distance:
  * Read 2 floating-point numbers: distance and time
  * Calculate the speed needed to travel a given distance for given time
  * Print the calculated result
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|15<br>2|7.5  | 
[/slide]

[slide]
# Problem: Currency Converter
[code-task title="Currency Converter" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      // Write code here
    }
}
```
[/code-editor]
[task-description]
* Write a program to convert from USD to EUR:
  * Read a **floating-point number**: the **dollars** to be converted 
  * Convert dollars to euro (use fixed rate of dollars to euro: **0.88**)
  * Print the converted value in **euro**
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|17|14.96 | 
|87|76.56|
[/slide]

[slide]
# Solution: Currency Converter
[code-task title="Currency Converter" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      double dollars = double.Parse(Console.ReadLine());
      double euros = dollars * 0.88; 
        Console.WriteLine(euros);
    }
}
```
[/code-editor]
[task-description]
* Write a program to calculate the speed by time and distance:
  * Read 2 floating-point numbers: distance and time
  * Calculate the speed needed to travel a given distance for given time
  * Print the calculated result
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|17|14.96 | 
|87|76.56|
[/slide]