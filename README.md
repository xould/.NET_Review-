# .NET_Review-
Study .NET and Microsoft Copilot

What is .NET:  powerful platform for creating scalable, **cross-platform web**, desktop, and mobile applications. 

* .net run on 3 different servers: Kestrel, HTTP Sys(TLS-transport layer security) performance good), IS
[david fouler, steven tobe, mayoni stevenson -.net blog]

*  ASP.NET for web - simplify dev of dynamic web applications => MVC architecture
by providing a consistent, OOP environment
*.NET8 => AOT(Ahead-of-Time) compilation, which allows applications to be compiled directly to the native code, eliminating need for JIT (Just-in-time) at runtime”
*Blazor => .NET front-end framework

*NET CLI(command line interface) allows u to manage .NET projects with speed and precision
*packages : collections of reusable code that you can include in your projects to add functionality w/o building everything from scratch.
=> .NET package ( **NuGet**)

1) Web applications: **ASP.NET** allows the development of dynamic and scalable web applications through frameworks like MVC, Razor Pages, and Blazor.

Example: Stack Overflow uses .NET Core to power its high-performance web applications, benefiting from increased scalability and reduced complexity.

2) Mobile applications:  Using **.NET MAUI** (the successor to **Xamarin**, which reached end-of-life in May 2024), developers can build native mobile apps for both iOS and Android from a single codebase, speeding up development and reducing maintenance.  

3) AI and machine learning: The **ML.NET** library enables developers to add machine learning features to .NET applications, enhancing data-driven insights.


---------------------------------------------------
_Key components of .NET Framework_
1. CLR (Common Language Runtime) - allows code written in multiple programming languages to run as a single program by compiling that code into CIL(intemediary)
2. BCL (Base Class Library) - provides a standardized collection of classes, interface, and value types for .NET development => Cohesive/ Consistent

* Limitations: tightly coupled to only Windows (x macOS and Linux) / Monolithic structure(more components than necessary)

  
.NET includes tools and features that make it easy to create, deploy, and manage applications in the Cloud (like Azure)

-----------------------------------------------------
.Net : top-level statements = I can write C# code w/o using a namespace, wrapper class or main method

control structure : if/else statement , switch statement (simplify complex conditional logic)
if (userInput == correctPassword)
{
  access = true;
  }
else
{
  access = false;
  }
