# C# 7 and .NET Core 2.0 High Performance
This is the code repository for [C# 7 and .NET Core 2.0 High Performance](https://www.packtpub.com/application-development/c-7-and-net-core-20-high-performance?utm_source=github&utm_medium=repository&utm_campaign=9781788470049), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
While writing an application, performance is paramount. Performance tuning for realworld applications often involves activities geared toward fnding bottlenecks; however, this cannot solve the dreaded problem of slower code. If you want to improve the speed of your code and optimize an application's performance, then this book is for you. C# 7 and .NET Core 2.0 High Performance begins with an introduction to the new features of what?explaining how they help in improving an application's performance. 

Learn to identify the bottlenecks in writing programs and highlight common performance pitfalls, and learn strategies to detect and resolve these issues early. You will explore multithreading and asynchronous programming with .NET Core and learn the importance and effcient use of data structures. This is followed with memory management techniques and design guidelines to increase an application’s performance. Gradually, the book will show you the importance of microservices architecture for building highly performant applications and implementing resiliency and security in .NET Core. 

After reading this book, you will learn how to structure and build scalable, optimized, and robust applications in C#7 and .NET.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.


The code will look like the following:
```
public static IWebHost BuildWebHost(string[] args) => 
  WebHost.CreateDefaultBuilder(args) 
    .UseMetrics() 
    .UseStartup<Startup>() 
    .Build(); 
```

This book is for .NET developers who want to improve the speed of their application's code or who simply want to take their skills to the next level, where they can develop and produce quality applications that are not only performant but also adhere to the industry best practices. Basic C# knowledge is assumed.

## Related Products
* [C# 7 and .NET Core 2.0 Blueprints](https://www.packtpub.com/application-development/c-7-and-net-core-20-blueprints?utm_source=github&utm_medium=repository&utm_campaign=9781788396196)

* [C# 7.1 and .NET Core 2.0 – Modern Cross-Platform Development - Third Edition](https://www.packtpub.com/application-development/c-71-and-net-core-20-%E2%80%93-modern-cross-platform-development-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788398077)

* [.NET Core 2.0 By Example](https://www.packtpub.com/application-development/net-core-20-example?utm_source=github&utm_medium=repository&utm_campaign=9781788395090)
