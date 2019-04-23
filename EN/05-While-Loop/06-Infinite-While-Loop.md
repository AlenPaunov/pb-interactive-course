[slide]
# Infinite While Loop
- Repeating a block of code an **infinite number of times**
- Infinite ***while*** loops are caused when the check condition is always evaluated to ***true***
```csharp
while(true)
{
}
```
[/slide]

[slide]
# Infinite While Loop: Example
```csharp
int number = 1;
string command = "Add";
while (command != "END") // Always evaluated to true
{
  Console.WriteLine(number);
}
```
[/slide]