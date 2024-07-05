C # notes

C# (C-Sharp) is a programming language developed by Microsoft that runs on the .NET Framework.
The first version was released in year 2002. The latest version, C# 11, was released in November 2022.
C# is used to develop web apps, desktop apps, mobile apps, games and much more.

framework -> Complete development environment
CLR-> runtime environment for .net

BOOT- suceesful loading of OS

containers--> hold data

C# prperties:
-->The Properties have accessors that are used to set, get or compute their values.
-->provide controlled access to them through getter and/or setter methods. 

arrays are objects.
static member - share common all objects
## non static member can we use both static and non-static.
## But static member can use only static member functions.

## can we write only static block ---> No    but in java yes

Abstract class --> Only have one abstract method
			   --> only method signature are there, no body is present

Why interface ?
--> loose couple(own implementation)
--> multiple inheritance
---------------------------------------------------------------------------------
String --> class
string --> allias of System.String

<Button x:Name="GoBack" Content="Go" Click="GoBackClick" />


            string str9 = "abc";
            string str10 = "def";
            str9 += str10;

string:
iterpolated string -->$

var info = (fname: "hemant", lname: "shah",desg: "Academic head");
---------------------------------------------------------------------------
cl.exe --> complier and linker
link.exe -->  linker

IL		-->intemediate language
msil 	-->microsoft intermediate language
ildasm.exe-->intermediate language disassemble

-------------------------------------------------------------------------
boxing-implicity called
unboxing - sometime we explicitly call
--------------------------------------------------------------------------		
Thread safe--> synchronized , mutually exculsive thread ,concurrent
concurrent - synchronous
collections- asynchronous

logs -> entry or exit point
strongly typed -> beacuse autoboxing not happens 


------------------------------------------------------------------------------------------------
Generics:
-->It is a concept that allows us to define classes and methods with placeholder. 
-->Compiler replaces these placeholders with specified type at compile time. 
-->The concept of generics is used to create general purpose classes and methods.
-->Type-safety

why generics?
-->for collection framework
--> for type safe
----------------------------------------------------------------------------------------------------
Collections-->
-->Group of objects
-->Predefined library of container classes which has predefine operation for insertion,deletion,searching,etc
-->All the classes are of generic types.
-->Every conatiner is implemented by templated or generics.

why collection?
--> directly implement that functions which are already defined in library
--> predefined algorithm and their implementation
------------------------------------------------------------
Delegates:
-->delegate is a reference to the method. 
-->It works like function pointer in C and C++. 
-->But it is objected-oriented, secured and type-safe than function pointer.
-->It stored in arrays.
-->It can be static or instance method;
-->Delegates is derived class of System.Delegate.
----------------------------------------------------------------
Anonmoyous Function:
-->A function without name is known as anonymous function.
-->Two types of anonymous functions:
		Lambda Expressions
		Anonymous Methods
----------------------------------------------------------------
Lamda Expression:
-->Lambda expression is an anonymous function which we can use to create delegates.
-->use to create anonmoyous class.
-->declaration operator
-->(input-parameters) => expression

---------------------------------------------------------------

Collection in C#:
-->List
-->HashSet
-->SortedSet
-->Stack
-->Queue
-->LinkedList
-->Dictionary
-->SortedDictionary
-->SortedList

---------------------------------------------------------------------

Linq-->
linq to objects
linq to datasets
linq to sql
linq to entities
linq to Xml

-->return objects not primitive value
