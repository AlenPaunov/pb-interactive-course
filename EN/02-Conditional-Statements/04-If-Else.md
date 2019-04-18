[slide]
# Simple Conditions: if-else
* If the condition is ***false***, we may execute another code using the ***еlse*** block
```csharp
if (…)
{
   // Condition is true
}
else
{
   // Condition is false
}
```
[/slide]

[slide]
# Block of Code
- The curly brackets ***{}*** introduce a **block** (a group of commands)
In case the ***if*** statement does **not** have curly brackets, only the code on the **next line** will be executed
```csharp
string color = "red";
if (color == "red") 
  Console.WriteLine("tomato");
else
  Console.WriteLine("banana");
Console.WriteLine("lemon"); /* <- Always executed */
```
```csharp
string color = "red";
if (color == "red")
{
  // Block of 2 commands
  Console.WriteLine("tomato");
  Console.WriteLine("strawberry"); 
}
else
{
  // Block of 2 commands
  Console.WriteLine("banana");
  Console.WriteLine("lemon");
}
```
[/slide]