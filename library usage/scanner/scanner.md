# How to use Scanner

## Import

One the top of the .java file, write the code

```java
import java.util.Scanner;
```

Then write
```java
Scanner scanner = new Scanner(System.in);
```
somewhere in your code

After using the scanner, don't forget to close it! It will not affect the overall program but it is a good practice to close the scanner after usage.
```java
scanner.closed()
```

## Prompt

* When prompting the user, please use `System.out.print()` (instead of `println()` as this will allow the user to enter the input in the same line.
