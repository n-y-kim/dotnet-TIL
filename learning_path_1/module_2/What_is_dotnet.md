# What is .NET?

When someone uses the term ".NET", what they mean changes by the context. In this specific unit, we will define .NET by looking at it as an **ecosystem**.

## .NET is an ecosystem for application development

### Use .NET languages & compilers to run applications in the .NET runtime

SW developers use .NET lang like C# and F# to write code.
To run the code, the **.NET compiler** is a program that converts the code into a special language called **IL** (Intermediate Language). The .NET compiler saves the IL code into a file called a .NET assembly. By compiling the code into an intermidate format, you can use the same code on different platforms.

C#(code) ➡️ compile(compiler) ➡️ IL(.NET assembly) ➡️ execute(.NET runtime)

- C# and .NET are distinct.
- C# is a programming language. As a syntax, it can reference & call methods defined in .NET code libraries, or assemblies.
- We use C# compiler that's installed with the .NET SDK to create an assembly from the C# code.

### Use .NET application frameworks & libraries to harness prebuilt functionality

An application framework combines several related libraries, along with starter projects, file templates, code generators, and other tools. You can use these resources to build entire applications for a specific purpose. These application frameworks are known as app models. For example, popular .NET application frameworks are available for app models like web development, desktop and mobile development, and game development.

#### Major app models
<table>
<thead>
<tr>
<th>App model</th>
<th>Framework</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td>Web</td>
<td>ASP.NET Core</td>
<td>The framework for building server-side logic.</td>
</tr>
<tr>
<td>Web</td>
<td>ASP.NET Core MVC</td>
<td>The framework for building server-side logic for web pages or web APIs.</td>
</tr>
<tr>
<td>Web</td>
<td>ASP.NET Core Razor Pages</td>
<td>The framework for building server-generated HTML.</td>
</tr>
<tr>
<td>Web client</td>
<td>Blazor</td>
<td>Blazor is a part of ASP.NET Core. Its two modes allow for either Document Object Model (DOM) manipulation via sockets as a communication vehicle for running server-side code, or a WebAssembly implementation for running compiled C# on a browser.</td>
</tr>
<tr>
<td>Desktop</td>
<td>WinForms</td>
<td>A framework for building &quot;battleship gray&quot; Windows-style applications.</td>
</tr>
<tr>
<td>Desktop</td>
<td>Windows Presentation Foundation (WPF)</td>
<td>A framework for building dynamic desktop applications that conform to different form factors. WPF allows form elements to perform movement, fades, glides, and other effects with the help of a rich library of animations.</td>
</tr>
<tr>
<td>Mobile</td>
<td>Xamarin</td>
<td>Allows .NET developers to build apps for iOS and Android devices.</td>
</tr>
</tbody>
</table>

