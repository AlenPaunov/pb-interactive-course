[slide]
# Problem: Sum Digits
[code-task title="Sum Digits" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads a number from the console
    - **Sums** the **digits** of a number
    - Prints the sum
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5634|18|
[/slide]

[slide]
# Solution: Sum Digits
[code-task title="Sum Digits" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      int n = int.Parse(Console.ReadLine());
      int sum = 0;
      while (n > 0)
      {
        sum += n % 10;
        n /= 10;
      }
      Console.WriteLine(sum);
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads a number from the console
    - **Sums** the **digits** of a number
    - Prints the sum
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5634|18|
[/slide]

[slide]
# Problem: Favorite Book
[code-task title="Favorite Book" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
  - Reads a **book's name** from the console
  - Receives names until it gets the **same book**
  - Prints **"Book found!"** and stops afterwards
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|Alice in Wonderland<br>Winnie the Pooh<br>Peter Pan<br>Alice in Wonderland|Book Found!|
[/slide]

[slide]
# Solution: Favorite Book
[code-task title="Favorite Book" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      string favoriteBook = Console.ReadLine();
      string book = Console.ReadLine();
      while(book != favoriteBook)
      {
        book = Console.ReadLine();
      }
      Console.WriteLine("Book found!");
    }
}
```
[/code-editor]
[task-description]
- Write a program, which: 
  - Reads a **book's name** from the console
  - Receives names until it gets the **same book**
  - Prints **"Book found!"** and stops afterwards
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|Alice in Wonderland<br>Winnie the Pooh<br>Peter Pan<br>Alice in Wonderland|Book Found!|
[/slide]

[slide]
# Problem: Min and Max
[code-task title="Min and Max" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
  - Receives integers until **"END"**
  - Prints the **biggest** and the **smallest** integer
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|10<br>20<br>304<br>0<br>50<br>END|Max number: 304<br>Min number: 0|
[/slide]

[slide]
# Solution: Min and Max
[code-task title="Min and Max" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      string line = Console.ReadLine();
      int min = int.MaxValue;
      int max = int.MinValue;
      while (line != "END") {
        int n = int.Parse(line);
        if (n < min)
          min = n;
        if (n > max)
          max = n;
        line = Console.ReadLine();
      } 
      // TODO: Print output
    }
}
```
[/code-editor]
[task-description]
- Write a program, which: 
  - Receives integers until **"END"**
  - Prints the **biggest** and the **smallest** integer
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|10<br>20<br>304<br>0<br>50<br>END|Max number: 304<br>Min number: 0|
[/slide]