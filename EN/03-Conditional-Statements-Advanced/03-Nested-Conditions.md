[slide]
# Nested Conditions
- An ***if-else*** statement can be nested within another ***if-else*** statement
```csharp
if (expression)
{
  if (nested expression)
    // Some code
  else
    // Some code
} 
```
- Only if the first condition is true the nested one is checked
```csharp
if (expression)
{
  if (nested expression)
    // Some code
  else
    // Some code
    // Executes when the nested expression is false
}
```
- Deep nesting is not recommended
  - Use up to 3 nested levels
[/slide]

[slide]
# Problem: Marketplace
[code-task title="Marketplace" executionStrategy="csharp-dot-net-core-code" requiresInput]
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
- Read a **product** and **day** from the console
- Print the **price**, formatted to 2nd digit, based on the price table:
[/task-description]
[code-io /]
[/code-task]

|Product|Weekday|Weekend| 
|-------|-------|-------|
|Banana|2.50|2.70|
|Apple|1.30|1.60|
|Kiwi|2.20|3.00|

# Sample Input and Output

|Input|Output|
|-----|------|
|Banana<br>Weekday|2.50|

[/slide]