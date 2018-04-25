# Network Programming with Rust
This is the code repository for [C# 7 and .NET Core 2.0 High Performance](https://www.packtpub.com/application-development/c-7-and-net-core-20-high-performance?utm_source=github&utm_medium=repository&utm_campaign=9781788470049), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Rust is low-level enough to provide fine-grained control over memory while providing safety through compile-time validation. This makes it uniquely suitable for writing low-level networking applications.

This book is divided into three main parts that will take you on an exciting journey: building a fully functional web server. The book starts with a solid introduction to Rust and essential networking concepts. This will lay a foundation for, and set the tone of, the entire book. It takes an in-depth look at using Rust for networking software. Starting with client-server networking using sockets to IPv4/v6, DNS, TCP, UDP, you will also learn about serializing and deserializing data using serde. The book shows how to communicate with REST servers over HTTP and implement asynchronous network programming using the Tokio stack. Given the importance of security for modern systems, you will see how Rust supports common primitives such as TLS and public key cryptography.

After reading this book, you will be more than confident enough to use Rust to build effective networking software.

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
