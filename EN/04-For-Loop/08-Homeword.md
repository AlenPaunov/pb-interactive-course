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

[slide]
# Problem: Equal Pairs
[code-task title="Equal Pairs" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads number n and n pairs of numbers
    - Prints "Yes, value={sum}", if the sum of all pairs is the same
    - Otherwise, prints "No, maxdiff={diff}"
    - diff is the max difference in the sum between two pairs
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2<br>-1<br>0<br>0<br>-1|Yes, value=-1|
[/slide]

[slide]
# Solution: Equal Pairs
[code-task title="Equal Pairs" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int n = int.Parse(Console.ReadLine());
        int prevSum = 0;
        int maxDiff = 0;
        bool areEqual = true;
        for (int i = 0; i < n; i++) {
        int a = int.Parse(Console.ReadLine());
        int b = int.Parse(Console.ReadLine());
        if (i > 0) {
            if (maxDiff < Math.Abs(prevSum - a - b))
            maxDiff = Math.Abs(prevSum - a - b);
            if (areEqual && a + b != prevSum) 
            areEqual = false;
        }
        prevSum = a + b;
        }
        // TODO: Print the result
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads number n and n pairs of numbers
    - Prints "Yes, value={sum}", if the sum of all pairs is the same
    - Otherwise, prints "No, maxdiff={diff}"
    - diff is the max difference in the sum between two pairs
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2<br>-1<br>0<br>0<br>-1|Yes, value=-1|
[/slide]

[slide]
# Problem: Bigger Number
[code-task title="Bigger Number" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads n - number representing amount of input numbers
    - Reads n numbers
    - Finds and prints the biggest number
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3<br>40<br>90<br>50<br>|90|
|-3<br>-40<br>-90<br>-50<br>|-40|
[/slide]

[slide]
# Solution: Bigger Number
[code-task title="Bigger Number" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int n = int.Parse(Console.ReadLine());
        int maxNumber = int.MinValue;
        for (int i = 1; i <= n; i++) {
        int number = int.Parse(Console.ReadLine());
        if (number > maxNumber) {
            maxNumber = number;
        }
        }
        Console.WriteLine(maxNumber);
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads n - number representing amount of input numbers
    - Reads n numbers
    - Finds and prints the biggest number
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3<br>40<br>90<br>50<br>|90|
|-3<br>-40<br>-90<br>-50<br>|-40|
[/slide]

[slide]
# Problem: Zig Zag Sum
[code-task title="Zig Zag Sum" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads n - number representing amount of input numbers
    - Reads n numbers 
    - For every even line adds the number to the result
    - For every odd line subtracts the number from the result
    - Prints the result
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2<br>10<br>20|-30|
[/slide]

[slide]
# Solution: Zig Zag Sum
[code-task title="Zig Zag Sum" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int n = int.Parse(Console.ReadLine());
        int sum = 0;
        for (int i = 1; i <= n; i++) {
        int m = int.Parse(Console.ReadLine());
        if (i % 2 == 0) sum += m;
        else sum -= m;
        }
        Console.WriteLine(sum);
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads n - number representing amount of input numbers
    - Reads n numbers 
    - For every even line adds the number to the result
    - For every odd line subtracts the number from the result
    - Prints the result
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2<br>10<br>20|-30|
[/slide]

[slide]
# Problem: Divide Without Remainder
[code-task title="Divide Without Remainder" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads n and n numbers
    - Finds in percentage how many of them can divide without remainder at 2, 3 and 4
    - Prints percentages p1, p2 and p3, formatted to the second digit
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3<br>3<br>6<br>9|33.33%<br>100.00%<br>0.00%|
|3<br>4<br>6<br>3|66.67%<br>66.67%<br>33.33%|
[/slide]

[slide]
# Solution: Divide Without Remainder
[code-task title="Divide Without Remainder" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int n = int.Parse(Console.ReadLine());
        double p1 = 0.0;
        double p2 = 0.0;
        double p3 = 0.0;
        for (int i = 0; i < n; i++) {
        int num = int.Parse(Console.ReadLine());
        if (num % 2 == 0) p1++;
        if (num % 3 == 0) p2++;
        if (num % 4 == 0) p3++;
        }
        var resultP1 = (p1 / n) * 100;
        var resultP2 = (p2 / n) * 100;
        var resultP3 = (p3 / n) * 100;
        // TODO: Print the result
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads n and n numbers
    - Finds in percentage how many of them can divide without remainder at 2, 3 and 4
    - Prints percentages p1, p2 and p3, formatted to the second digit
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3<br>3<br>6<br>9|33.33%<br>100.00%<br>0.00%|
|3<br>4<br>6<br>3|66.67%<br>66.67%<br>33.33%|
[/slide]