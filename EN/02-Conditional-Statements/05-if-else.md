[slide]
# Simple Conditions - if-else
If the condition is **false**, we may execute another code - using the statement **еlse** 

```java
if (...) {
   // Condition is true
} else {
   // Condition is false
}
```
[/slide]

[slide]
# Block of Code
The curly brackets **{}** introduce a block (a group of commands)
In case the **if** statement does **not** have curly brackets, only the code on the **next line** will be executed

```java
String color = "red";
if (color.equals("red")) {
  System.out.println("tomato");
}else{
  System.out.println("banana");
}
System.out.println("lemon"); // Always executed
```

[/slide]

[slide]
# Block of Code

```java
String color = "red";
if (color.equals("red")) {    
    //block of 2 commands
  System.out.println("tomato");
  System.out.println("strawberry"); 
} else {
  //block of 3 commands
  System.out.println("banana");
  System.out.println("lemon");
  System.out.println("pear");
}

```

[/slide]

[slide]
# Problem: Even or Odd
[code-task title="Even or Odd" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
   public static void main(String[] args) {
      // Write code here
    }
}
```
[/code-editor]
[task-description]

Write a program, which: 
* Checks whether a number is **even** or **odd**
    * If it's even, it should print "**even**"
    * If it's odd, it should print "**odd**"

[/task-description]
[code-io /]
[/code-task]



## Sample Input and Output
|Input|Output|
|-----|------|
|4|even|
|7|odd|

[/slide]

[slide]
# Solution: Even or Odd

[code-task title="Even or Odd" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int num = Integer.parseInt(scanner.nextLine());
        if (num % 2 == 0) {
            System.out.println("even");
        } else {
            System.out.println("odd");
        }
    }
}
```
[/code-editor]
[task-description]

Write a program, which: 
* Checks whether a number is **even** or **odd**
    * If it's even, it should print "**even**"
    * If it's odd, it should print "**odd**"

[/task-description]
[code-io /]
[/code-task]



## Sample Input and Output
|Input|Output|
|-----|------|
|4|even|
|7|odd|

[/slide]

[slide]
# Problem: Greater Number
[code-task title="Greater Number" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
   public static void main(String[] args) {
      // Write code here
    }
}
```
[/code-editor]
[task-description]

Write a program, which:
* Reads two **integers**
* Finds the greater number
* Prints "**Greater number:** " + the **greater** number

[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output
|Input|Output|
|-----|------|
|5|Greater number: 8|
|8|

[/slide]

[slide]
# Solution: Greater Number
[code-task title="Greater Number" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int num1 = Integer.parseInt(scanner.nextLine());
        int num2 = Integer.parseInt(scanner.nextLine());
        if (num1 > num2) {
            System.out.println("Greater number: " + num1);
        } else {
            System.out.println("Greater number: " + num2);
        }
    }
}
```
[/code-editor]
[task-description]

Write a program, which:
* Reads two **integers**
* Finds the greater number
* Prints "**Greater number:** " + the **greater** number

[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output
|Input|Output|
|-----|------|
|5|Greater number: 8|
|8|

[/slide]