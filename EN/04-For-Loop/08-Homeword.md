[slide]
# Problem: Number Sequence
[code-task title="Number Sequence" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads n representing the count of numbers to read next
    - Finds the max and the min numbers
    - Prints them on the console
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5<br>10<br>20<br>304<br>0<br>50|Max number: 304<br>Min number: 0|
[/slide]

[slide]
# Solution: Number Sequence
[code-task title="Number Sequence" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int n = int.Parse(Console.ReadLine());
        int min = int.MaxValue;
        int max = int.MinValue;
        for (int i = 0; i < n; i++)
        {
            int num = int.Parse(Console.ReadLine());
            if (num < min) min = num;
            if (num > max) max = num;
        }
        Console.WriteLine($"Max number: {max}");
        Console.WriteLine($"Min number: {min}");
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads n representing the count of numbers to read next
    - Finds the max and the min numbers
    - Prints them on the console
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5<br>10<br>20<br>304<br>0<br>50|Max number: 304<br>Min number: 0|
[/slide]

[slide]
# Problem: Power Of Numbers
[code-task title="Power Of Numbers" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads p – the power and n – the number
    - Prints the result of n powered by p
    - Don't use Math.Pow()
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5<br>2|32|
|4<br>3|81|
[/slide]

[slide]
# Solution: Power Of Numbers
[code-task title="Power Of Numbers" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int p = int.Parse(Console.ReadLine());
        int n = int.Parse(Console.ReadLine());
        int result = 1;
        for(int i = 0; i < p; i++)
        {
          result = result * n;
        }
        Console.WriteLine(result);
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads p – the power and n – the number
    - Prints the result of n powered by p
    - Don't use Math.Pow()
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5<br>2|32|
|4<br>3|81|
[/slide]