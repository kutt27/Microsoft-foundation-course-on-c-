### Hello World

```c#
Console.WriteLine("Hello World!");

// warning
// this is wrong

console.WriteLine("Hello World!");
Console.WriteLine('Hello World!');
```

Difference between 'Console.WriteLine("Hello World!")' & 'Console.Write("Hello World!")' is 'WriteLine' print the Literal string into a line and appends a new line after that on the other hand 'Write' just print the Literal String to the terminal without a new line.

### Breaking down the code

- Console : is a part of class were the methods reside.
- "Hello World": is the literal string
- dot: dot is used for accessing the method 'WriteLine' inside of the class 'Console'
- semicolon: a statement operator

### Challenge: Write code in the .NET Editor to display two messages

The required output is:

```
This is the first line.
This is the second line.
```

Solution: 

```c#
Console.WriteLine("This is the first line.");
Console.Write("This is the second line.");
```

*Breakdown*: The first line prints the line and append a new line and then we print the output with write method only.
