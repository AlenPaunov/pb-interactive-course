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

[slide]
# Problem: Passwords
[code-task title="Passwords" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Generates custom **3 digit** passwords, which meet the following conditions:
        - The **first** digit is an **even** number
        - The **second** digit is an **odd** number
        - The **third** is the **product** of the first two
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|6|212 236 2510 414 4312 4520 616 6318 6530|
|5|212 236 2510 414 4312 4520|
[/slide]

[slide]
# Solution: Passwords
[code-task title="Passwords" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int n = int.Parse(Console.ReadLine());
        for (int i = 1; i <= n; i++)
        {
            for (int j = 1; j <= n; j++)
            {
                if (i % 2 == 0 && j % 2 != 0)
                {
                    Console.Write($"{i}{j}{i * j} ");
                }
            }
        }
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Generates custom **3 digit** passwords, which meet the following conditions:
        - The **first** digit is an **even** number
        - The **second** digit is an **odd** number
        - The **third** is the **product** of the first two
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|6|212 236 2510 414 4312 4520 616 6318 6530|
|5|212 236 2510 414 4312 4520|
[/slide]

[slide]
# Problem: Magic Number
[code-task title="Magic Number" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads a **number - n**, from the console
    - Finds all **3-digit numbers**:
        - Forming **n** as a product of the multiplication of their digits
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3|113<br>131<br>311|
|1|111|
[/slide]

[slide]
# Solution: Magic Number
[code-task title="Magic Number" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        int magicNumber = int.Parse(Console.ReadLine());
        for (int i = 1; i <= 9; i++)
        {
            for (int j = 1; j <= 9; j++)
            { 
                for (int k = 1; k <= 9; k++)
                {
                    if (i * j * k == magicNumber)
                    // TODO: Print {i}{j}{k}
                }
            }
        }
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads a **number - n**, from the console
    - Finds all **3-digit numbers**:
        - Forming **n** as a product of the multiplication of their digits
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3|113<br>131<br>311|
|1|111|
[/slide]

[slide]
# Problem: Travelling
[code-task title="Travelling" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
    - Reads a **destination** and **needed budget** for destination
    - Continues reading numbers - amounts of money, until they are **enough** for the destination
        - If it receives the command **"End"** the program ends
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|Philippines<br>1000<br>550<br>450|Going to Philippines!|
[/slide]

[slide]
# Solution: Travelling
[code-task title="Travelling" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
        string townName = string.Empty;
        double currentMoney = 0;
        while ((townName = Console.ReadLine()) != "End") 
        {
            double neededMoney = double.Parse(Console.ReadLine());
            while (currentMoney < neededMoney) 
            {
                double money = double.Parse(Console.ReadLine());
                currentMoney += money;
            }
            Console.WriteLine($"Going to {townName}!");
            currentMoney = 0;
        }
    }
}
```
[/code-editor]
[task-description]
- Write a program, which:
    - Reads a **destination** and **needed budget** for destination
    - Continues reading numbers - amounts of money, until they are **enough** for the destination
        - If it receives the command **"End"** the program ends
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|Philippines<br>1000<br>550<br>450|Going to Philippines!|
[/slide]