[slide]
# Nested Loops
- Statements that consist of several **loops** located **inside each other**
- **Nested loops** are used:
    - To execute an **action**, which **executes** multiple **actions**
    - To make more **complex** calculations and variations

```csharp
for (int i = 1; i <= n; i+=3) 
{
   for (int j = 1; j <= n; j+=3)
   {
      for (int k = 1; k <= n; k+=3)
      {
        // ...
      }
   }
}
```
[/slide]