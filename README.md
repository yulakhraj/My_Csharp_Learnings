# C# Notes

C# (C-Sharp) is a programming language developed by Microsoft that runs on the .NET Framework. The first version was released in 2002, and the latest version, C# 11, was released in November 2022. C# is used to develop web apps, desktop apps, mobile apps, games, and much more.

## Key Concepts

### Framework
- **Framework**: A complete development environment.
- **CLR (Common Language Runtime)**: The runtime environment for .NET.

### Boot
- **Boot**: Successful loading of the OS.

### Containers
- **Containers**: Hold data.

### C# Properties
- Properties have accessors (getters and setters) to set, get, or compute their values.
- Provide controlled access to class members.

### Arrays
- Arrays in C# are objects.

### Static Members
- Static members are shared among all objects.
- Non-static members can use both static and non-static members, but static members can only use other static members.

### Abstract Class
- An abstract class can have one or more abstract methods.
- Abstract methods have only method signatures; no body is present.

### Interfaces
- Provide loose coupling by allowing own implementation.
- Support multiple inheritance.

### Strings
- **String**: A class.
- **string**: Alias of System.String.

```csharp
<Button x:Name="GoBack" Content="Go" Click="GoBackClick" />
string str9 = "abc";
string str10 = "def";
str9 += str10;
```

# Advanced C# Concepts

## Compilers and Linkers

- **cl.exe**: Compiler and linker.
- **link.exe**: Linker.
- **IL (Intermediate Language)**: Microsoft's intermediate language.
- **ildasm.exe**: Intermediate language disassembler.

## Boxing and Unboxing

- **Boxing**: Implicitly called.
- **Unboxing**: Explicitly called sometimes.

## Thread Safety

- **Thread safe**: Synchronized, mutually exclusive threads, concurrent.
- **Concurrent**: Synchronous.
- **Collections**: Asynchronous.

## Generics

- Define classes and methods with placeholders, which the compiler replaces with specified types at compile time.
- Provide type safety.

## Collections

- Group of objects with predefined operations for insertion, deletion, searching, etc.
- Classes are of generic types.

## Delegates

- A reference to a method.
- Functions like function pointers in C and C++, but more secure and type-safe.
- Can be static or instance methods.
- Derived from `System.Delegate`.

## Anonymous Functions

- Functions without names.
- Types: Lambda Expressions, Anonymous Methods.

### Lambda Expressions

- Anonymous functions to create delegates.
- Used to create anonymous classes.
- Declaration operator: `=>`.

```csharp
(input-parameters) => expression
```

# Collections in C#

C# offers a variety of collections to manage and manipulate data efficiently:

- **List**: Represents a strongly typed list of objects that can be accessed by index.
- **HashSet**: Represents a collection of unique unordered elements.
- **SortedSet**: Represents a collection of unique sorted elements.
- **Stack**: Represents a last-in, first-out (LIFO) collection of objects.
- **Queue**: Represents a first-in, first-out (FIFO) collection of objects.
- **LinkedList**: Represents a doubly linked list of objects.
- **Dictionary**: Represents a collection of key/value pairs.
- **SortedDictionary**: Represents a collection of key/value pairs sorted by keys.
- **SortedList**: Represents a collection of key/value pairs that are sorted by keys.

## LINQ (Language Integrated Query)

LINQ provides a unified way to query data from different data sources. Here are some common LINQ providers in C#:

- **LINQ to Objects**: Querying in-memory objects.
- **LINQ to DataSets**: Querying datasets.
- **LINQ to SQL**: Querying relational databases using SQL.
- **LINQ to Entities**: Querying Entity Framework data models.
- **LINQ to XML**: Querying XML documents.


