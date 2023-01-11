## What happens to the code you write?

```cs
Console.WriteLine("Hello World!");
```

The hidden code:

```cs
using System;

public class Program
{
    public static void Main()
    {
        Console.WriteLine("Hello World!");
    }
}
```

- `System.Console.WriteLine` == `Console.WriteLine()`

## What happens to your code after it's inserted into the Main() method?
1. C# compiler compiles the code. If there are errors, it would stop and send you the error message.
2. If it succeeds, the .NET runtime opens the newly compiled .NET assembly. It looks for the Main() method and executes it.
3. .NET runtime evaluates each line of code.
4. When the code ends, the .NET runtime removes the program from its memory. The `WriteLine()` method is called and the output is displayed in the Output pane.

