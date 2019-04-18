[slide]
# Problem: Guess the Password
[code-task title="Guess the Password" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
- Write a program to check a password:
  - Read a string: the password guess
  - Print "Welcome" if the password guess is "s3cr3t!"
  - Print "Wrong password!" in all other cases 
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|s3cr3t!|Welcome|
|qwerty|Wrong password!|
[/slide]

[slide]
# Solution: Guess the Password
[code-task title="Guess the Password" executionStrategy="csharp-dot-net-core-code" requiresInput]
[code-editor language=csharp]
```
using System;
public class Program
{
  public static void Main()
    {
      string password = Console.ReadLine();
      if (password == "s3cr3t!") {
        Console.WriteLine("Welcome");
      }
      else {
        Console.WriteLine("Wrong password!");
      }
    }
}
```
[/code-editor]
[task-description]
- Write a program to check a password:
  - Read a string: the password guess
  - Print "Welcome" if the password guess is "s3cr3t!"
  - Print "Wrong password!" in all other cases 
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|s3cr3t!|Welcome|
|qwerty|Wrong password!|
[/slide]