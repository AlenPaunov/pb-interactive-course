[slide]
# Problem: Greeting
[code-task title="Greeting" executionStrategy="java-code" requiresInput]
[code-editor language="java"]
```
public class Program
{
  public static void main(String[] args) {
      // Write code here
  }
}
```
[/code-editor]
[task-description]
Write a **program**, which:

* Reads a user input - **name**, from the console
* Prints "Hello, \{name\}!", where \{name\} is the user input
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Solution: Greeting
[code-task title="Greeting" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```
public class Program
{
  public static void main(String[] args) {
    String name = scanner.nextLine();
    System.out.print("Hello, ");
    System.out.println(name);
  }
}
```
[/code-editor]
[task-description]
Write a **program**, which:

* Reads a user input - **name**, from the console
* Prints "Hello, \{name\}!", where \{name\} is the user input
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Concatenating Text and Numbers
```java
String firstName = "John";
String lastName = "Doe";
int age = 34;
String str = firstName + " " + lastName + " | " + age;
System.out.println(str); // John Doe | 34

```

```java
int a = 5;
int b = 11;
String str = "a + b = " + a + b;
System.out.println(str); // a + b = 511
```
[/slide]

[slide]
# Arithmetic Operators

[/slide]