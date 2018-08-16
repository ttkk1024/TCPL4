### Part I Introduction


This introduction gives an voerview of the major concepts and features of the C++ programming language and its standard library. It also provides an overivew of this book and explains the approach taken to hte description of the language facilities and their use. In addition, the intorductiory chapters present some background information about C++, the design of C++, and the use of C++.

Chapters

1 Notes to the Reader

2 A Tour of C++: The Basics

3 A Tour of C++: Abstraction Mechanisms

4 A Tour of C++: Containers and 
Algorithms

5 A Tour of C++: Concurrency and Utilities


### 01

Notes to the Reader


- The Structure of This Book
  Introduction; Basic Facilities; Abstraction Mechanisms; The Standard Library; Examples and Reference;

- The Design of C++
  Programming Styles; Type Checking; C Compatibility; Language, Libraries, and system

- Learning C++
  Programming in C++; Suggestions for C++ Programmers; Suggestions for C Programmers; Suggestins for Java Programmers

- History
  Timeline; The Early Year; The 1998 Standard; The 2011 STandard; What is C++ Used for?

- Advice
- References

#### 1.1 The Structure of This Book

A pure tutorial sorts its topics so that no concept is used before it has been introduced; it must be read linearly starting with page one. conversely, a pure reference manual can be accessed starting at any point; it describes each topic succinctly with references (forward anb backward) to related topics. Apure tutorial can in principle be read without prerequistes - it carefully describes all . Apure reference can be used only be someone famililiar with all fuundamental concepts and techniques. on a per-chapter or even on a per-section basis. If not, you can start at the beginnging,but try not to get bogged down in details. Use the index and the cross-references.

Making parts of the book relatively self-contained implies some repetition, but repetition also serves as review for people reading the book linearly. The book is heavily cross-referencd both to itself and to the ISO C++ standard. Experienced programmers can read the (relatively) quick "tour" of C++ to gain the overview needed to use the book as a reference.  This book consists of four parts:

- Part I   
Introduction: Chapter 1(this chapter) is a guide to this book and provides a bit of C++ background. Chapters 2-5 give a quick introduction to the C++ language and its standard library.

- Part II
Basic Facilities: Chapter 6-15 describes C++'s build-in types and the absic facilities for construcing programs out of them.

- Part III
Abstraction Mechanisms: Chapters 16-29 describe C++'s abstraction mechanisms and thier use for object-oriented and generic programming.

- Part IV
Chapter 30-44 provide an overview of the standard library and a discussion of compatibility issues.


#### 1.1.1 Introduction

This chapter, Chapter 1, provides an overview of this book,some hints about how to use it, and some background information about C++ and its use. You are encouraged to skim throught it, read what appears interesting, and return to it after reading other parts of the book. Please do not feel obliged to read it all carefully before proceeding.

The following chapters provide an overview of the major concepts and features of the C++ porgramming language and its standard library:

- Chapter 2 
A Tour of C++: The Basics describes C++'s medel of memory,computation, adn error handling.
- Chapter 3
A Tour of C++: ABstraction Mechanisms presents the language features supporting data abstraction, object-oriented programming, and generic programming.
- Chapter 4
A Tour of C++: Containers and Algorithms introduces strings, simple I/O, containers, and algorithms as provided by the standard library.
- Chapter 5
A Tour of C++: Concurrency and Utilites outlines the standard-library utilites related to resource management, concurrency, mahtematical computation,reuglar expression, and more.

This whirlwind tour of C++'s facilites aims to give the reader a taste of what C++ offers. In particular, it should convince readers that C++ has come a long way since the first, second, and third editions of this book.


#### 1.1.2 Basic Facilities

Part II focuses on the subset of C++ that supports the styles of programming traditionally done in C and similar languages. It introduces the notions of type,object, scope and storage. It presents the fundamentals of computation: expressions, statements and functions. Modulrity -- as supported by namscpacs, source files and exception handling - is also discussed:

- Chapter 6 
Types and Decalarations: Fundamental types,naming,scopes,initialization, simple type deduction, object lifetimes, and type aliases
- Chapter 7
Pointers, Arrays, and References
- Chapter 8
Structures, Unions, and Enumerations
- Chapter 9
Statements: Declarations as statements, Selection statements( __if__ and __switch__),iteration statements( __for__ , __while__ , and __do__), __goto__ , and comments
- Chapter 10
Expressions: A desk caculator example, survey fo operators, constant expressions, and implicit type conversion
- Chapter 11
Select Operations: Logical operators, the conditional expression, increment and decrement, free store( __new__ and __delete__ ), __{}__-lists, lambda expressions, and explicit type conversion(__static_cast__ and __const_cast__)



