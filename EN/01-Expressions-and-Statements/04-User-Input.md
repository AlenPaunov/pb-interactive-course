[slide]
# Reading User Input
Everything we receive from the console comes as a ***String***

Reading user input is done with a simple command:
```java
Scanner scanner = new Scanner(System.in);
String name = scanner.nextLine();
```
Everything we print on the console is converted to ***String***
```java
System.out.println("Hello world!");
```
[/slide]

[slide]
# Formatting Output
Formatting text with **placeholders**
```java
String firstName = "John";
String lastName = "Doe";
System.out.printf("%s %s", firstName, lastName);  // John Doe
```
Formatting numbers with **placeholders**
```java
double a = 5.123;
double b = 6.456;
System.out.printf("%.2f", a + b); // 11.58
```
[/slide]

[slide]
# Reading User Input
A program which **read**s a name from the console and **prints** it:
```java
Scanner scanner = new Scanner(System.in);
String name = scanner.nextLine();
System.out.println(name);
```
The result from the execution would be:
```
Sample Input
```
[image src="https://github.com/AlenPaunov/pb-interactive-course/blob/01-java-expressions-and-statements/assets/expressions-and-statements-2.png"/]
```
Sample Output
```
[/slide]