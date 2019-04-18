[slide]
# Logical Operators
- Used to perform logical operations
- The logical operators are:
  - AND (**&&**)
  - OR (**||**)
  - Logical negation (**!**)
- Brackets **()** change the order
[/slide]

[slide]
# Logical Operators: Explanation
[image src="https://github.com/AlenPaunov/pb-interactive-course/blob/03-conditional-statements-advanced/assets/03-conditional-statements-advanced-1.png"/]
[/slide]

[slide]
# Logical AND (&&)
- Returns the boolean value true if operands are true and returns false otherwise
```csharp
if (x >= x1 && x <= x2 && y >= y1 && y <= y2)
```
[/slide]
[slide]
# Problem: Bonus Points
[code-task title="Bonus Points" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
- Write a program that applies bonus to given points
  - If points are between 0 and 3, adds 5
  - If points are between 4 and 6, adds 15
  - If points are between 7 and 9, adds 20
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|19|
[/slide]

[slide]
# Solution: Bonus Points
[code-task title="Bonus Points" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      int points = int.Parse(Console.ReadLine());
      if (points >= 0 && points <= 3)
        points += 5;
      else if (points >= 4 && points <= 6)
        points += 15;
      else if (points >= 7 && points <= 9)
        points += 20;

      Console.WriteLine(points);
    }
}
```
[/code-editor]
[task-description]
- Write a program that applies bonus to given points
  - If points are between 0 and 3, adds 5
  - If points are between 4 and 6, adds 15
  - If points are between 7 and 9, adds 20
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|19|
[/slide]