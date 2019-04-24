[slide]
# Problem: Building
[code-task title="Building" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Prints information about **apartments** (odd rows), **offices** (even rows) and the **last floor** (last row)
    - Apartment ***"A\{buildingNum\}\{apartmentNum\}"***
    - Office ***"O\{floorNum\}\{officeNum\}"***
    - Floor ***"L\{buildingNum\}\{apartmentNum\}"***
    - The numbers always start from **0**
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|6<br>4|L60 L61 L62 L63<br>A50 A51 A52 A53<br>O40 O41 O42 O43<br>A30 A31 A32 A33<br>O20 O21 O22 O23<br>A10 A11 A12 A13|
[/slide]

[slide]
# Solution: Building
[code-task title="Building" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int floors = int.Parse(Console.ReadLine());
        int rooms = int.Parse(Console.ReadLine());
        for (int i = floors; i >= 1; i--) 
        {
            for (int j = 0; j < rooms; j++) 
            {
                if (i == floors) // Print L{i}{j} Last Floor
                if (i % 2 == 0) // Print O{i}{j} Office
                if (i % 2 == 1) // Print A{i}{j} Apartment
            } 
            Console.WriteLine();
        }
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Prints information about **apartments** (odd rows), **offices** (even rows) and the **last floor** (last row)
    - Apartment ***"A\{buildingNum\}\{apartmentNum\}"***
    - Office ***"O\{floorNum\}\{officeNum\}"***
    - Floor ***"L\{buildingNum\}\{apartmentNum\}"***
    - The numbers always start from **0**
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|6<br>4|L60 L61 L62 L63<br>A50 A51 A52 A53<br>O40 O41 O42 O43<br>A30 A31 A32 A33<br>O20 O21 O22 O23<br>A10 A11 A12 A13|
[/slide]