[slide]
# For Loop
- Allows code to be executed **repeatedly**
- Repeating while the condition is met
```csharp
for (initialization; condition; step)
{
    // Body of the for loop
}
```
- **Initialization** - initializes the variable
- **Condition** - evaluates the condition
- **Step** - updates the initialized value
[/slide]

[slide]
# For Loop: Example
```csharp
for (int i = 1;/*Initial value*/ i <= 10;/*Condition*/ i += 1 /*Step*/) 
{
  Console.WriteLine(i); // Loop body
}
```
[/slide]

[slide]
# Problem: Print Sum of N Numbers
[code-task title="Print Sum of N Numbers" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
- Write a program, which:
    - Reads number n from the console
    - Sums all numbers from 1 to n
    - Prints the sum on the console
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|15|
|6|21|
[/slide]