# Dot Net and C#


.NET framework is developed by Microsoft which provides an environment to run, debug and deploy code onto web services and applications by using tools and functionalities like libraries, classes, and APIs. 
It supports different languages like C#, Cobol, VB, Perl, etc.




### Table of Contents

| No. | Feature |
| --- | --------- |
|1  | [Main components of .NET framework](#Main-components) |
|2  | [How does the .NET framework work?](#framewrok-work) |
|3  | [What is CTS?](#cts) |
|4  | [Explain CLS](#cls) |
|5  | [What is JIT?](#jit) |
|6  | [What is the difference between int and Int32?](#int32) |

## ES2015 Or ES6

1. ### Main components of .NET framework

    .NET framework consists of 2 main components. They are:

      **Common Language Runtime**- It is an execution engine that runs the code and provides services that make the development process easier.
      **Framework Class Library**- It has pre-defined methods and properties to implement common and complex functions that can be used by .NET applications.


2. ### How does the .NET framework work?

    .NET framework-based applications that are written in supportive languages like C#, F#, or Visual basic are compiled to Common Intermediate Language (CIL).
    Compiled code is stored in the form of an assembly file that has a .dll or .exe file extension.
    When the .NET application runs, Common Language Runtime (CLR) takes the assembly file and converts the CIL into machine code with the help of the Just In Time(JIT)             compiler.
    Now, this machine code can execute on the specific architecture of the computer it is running on.
    
    ![image](https://user-images.githubusercontent.com/38435793/124603211-50a6ec00-de87-11eb-8e02-cb41b9e1c499.png)



3. ### What is CTS?
    CTS stands for Common Type System. It follows a set of structured rules according to which a data type should be declared and used in the program code. It is used to           describe all the data types that are going to be used in the application.

    We can create our own classes and functions by following the rules in the CTS. It helps in calling the data type declared in one programming language by other programming       languages.

4. ### Explain CLS
    **Common Language Specification (CLS)** helps the application developers to use the components that are inter-language compatible with certain rules that come with CLS. It also helps in reusing the code among all of the .NET-compatible languages.

5. ### What is JIT?
    JIT stands for Just In Time. It is a compiler that converts the intermediate code into the native language during the execution.
    
6. ### What is the difference between int and Int32?
There is no difference between int and Int32. Int32 is a type provided by the .NET framework class whereas int is an alias name for Int32 in the C# programming language.



    **[⬆ Back to Top](#table-of-contents)**


