[slide]
# Simple Conditions
* Check certain condition and take action according to the result
```csharp
if (condition) /*Boolean expression*/
{
  // Code for execution if
  // the condition is true
}
```
* The result is either ***true*** or ***false***
[/slide]

[slide]
# Problem: Freezing Weather
[code-task title="Freezing Weather" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
* Write a program to check for freezing weather:
  * Read a temperature in Celsius (a floating-point number)
  * **Check** whether the temperature is below zero
  * Print "Freezing weather!", if the temperature is equal or smaller than 0
[/task-description]
[code-io /]
[/code-task]

# Sample Input and Output
|Input|Output|
|-----|------|
|-2|Freezing weather!|
|4|(no output)|
[/slide]

[slide]
# Solution: Freezing Weather
[code-task title="Freezing Weather" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      double temperature = double.Parse(Console.ReadLine());
      if (temperature <= 0)
      {
        Console.WriteLine("Freezing weather!");
      }
    }
}
```
[/code-editor]
[task-description]
* Write a program to check for freezing weather:
  * Read a temperature in Celsius (a floating-point number)
  * **Check** whether the temperature is below zero
  * Print "Freezing weather!", if the temperature is equal or smaller than 0
[/task-description]
[code-io /]
[/code-task]

# Sample Input and Output
|Input|Output|
|-----|------|
|-2|Freezing weather!|
|4|(no output)|
[/slide]