# The C++ Programming Language 


## Fourth Edition


### Bjane Stroustrup



### Preface

C++ feels like a new language.That is,I can express my ideas more clearly,more simpley,and more directly in C++11 than I could in C++98. Furthermore,the resulting programs are better checked by the compiler and run faster.


In this book,I aim for completeness.I describe every language feature and standard-library component that a professional programmers is likely to need.For each,I provide:

- Rationale: What kinds of problems is is designed to help solve? What priciples underlie  the design? What are the fundamental limitations?
- Specifications: what is its definition?The level of dtail is chosend for the expert programmer; the aspiring language lawyer can flollow the many references to the ISO standard.
- Examples: How can it be used well by itself and in combination with other features? What are the key techniques and idioms?


The use of C++ has changed dramatically over the years and so has the language itself.From the point of view of aprogrammer,most of the changes have been imporvements.The current ISO 
standard C++(ISO/IEC 14882-2011,usually called C++11) is simply a far better tool fro writing quality software than were previous versions. How its ti a better tool?What kinds of programming styles and techniques does modern C++ support? What language and standard-library features support those techniques? What are the basic building blocks of elegant,correct,maintainable,and efficient C++ code? Those are the key questions answered by this book.Many answers are not the same as you would find with 1985,1995,or 2005 vintage C++: progress happens.

C++ is a general-purpose programming language emphasizing the design and use of type-rhic lightweight abstractions. It is particularly suited for resource-constrained applicatons,such as those found in software infrastructures.C++ rewards the programmer who takes the time to master techniques for writing quality code. C++ is a language for someone who takes the task fo programming seriously. Our civlization depends critically on software; it had better be quality software.

There are billions of lines of C++ deployed.This pust a preminum on stability, so 1985 and 1995 C++ code still works and will continue to work for decades。 However, for call applications, you can do better with modern C++; if you stick to older styles, you will be writing lower-quality and worse-performing code. The emphasis on stability also implies that standards-conforming code you write today will still work a couple of decades from now. All code in this book condorms to the 2011 ISO C++ standard.

This book is aimed at three audiences:
- C++ programmers who wnat to kenow what the latest ISO C++ standard has to offer,
- C programmers who wonder what C++ provides beyond C, and
- People with a background in application lanugaes, such as Java, C#, Python, and Ruby, lokking for something "closer to the machine" - something more flexible,somthing offering better compile-time checking, or something offering better performance.

Naturally, these three groups are not disjont - a profressional software developer masters moare than just one programming language.

This bok assumes that its reader are programmers. If you ask, "What's a fro-llop?" or "What's a compiler?" then this book is not (yet) for you; instead, I recommend my Programming: Principles and Practice Using C++ to get started with programming and C++. Furthermore, i assume that readers have some maturity as software developers. If you ask "Why bother testing?"or say, "All languages are basically the ssame;just show me hte syntax" ore are confident that there is a single language that is ideal for every taks, this is not the book for you.

What features does C++11 offer over and above C++98? A machine model suitable for modern computers with lots of cocurrency. Language and standard-library facilities for doing systems-level concurrent programming (e.g; using multicores). Regular expression handling,resource management pointers, random numbers, improved containers(incluing, hash tables), and more. General and uniform initialization, a simpler for-statement, ove semantics, basic Uincode support, lambdas, genral constant repressions, control over lcasss defaults, variadic templates, user-defined literals, and more. please remember that thoes libraires and language features exist to support programming techniques for devloping quality software. They are meant to be usede in combination -  as bricks in a building set - rather than to be used individually in relative isolation to solve a specific problem. A computer is a universal machine, and C++ serves it in that capacity. In particular, C++'s design aims to be suffciently flexible and general to cope with future problems undreamed of by its designers.

#### Acknowledgments

In additions to the people mentioned in the acknowledgment sections of the previous editions, I would like to thank Pete Becker,Hans-J. Boehm, Marshell Clow,Jonathan Coe, Lawrence Crowl, Walter Daugherty, J. Daniel Garcia, Robert harle, Greg Hickman, howard Hinnant, Brian Kernighan, Daniel krugler, Nevin Liber, Michel Michaud, Gary Powell, jan Christiaan wn Winkel, and Leor Zolmna. Withou thir help this book would have been much poorer.

Thanks to Howard Hinnant for answering many questins about the standard library.

Andrew Sutton is the author of the Origin library, which was the tested for much of the discussion fo emulating concepts in the template chapters, and of the matrix library that is the topic of Chapter 29. The Origin library is open source and can be found by searching the Web of "Origin" and "Andrew Sutton".


Thanks to my graduate design class dor finding more problems with the "Tour chapters " than anyoue else.


Had I been able to follow ervy piece of advice of my reviewers,the book would undoubtedly have been much imporved,but it would also have been undreds of pgess lssosnger. Every expert reviewer suggested adding technicl details, advanced examples, and many useful developemnt convertions; every novice reviewer(or educator) suggested adding examples; and most reviewers observed(correctly) that the book may be too long.


Thanks to Priceton University's Computer Science Deapartment, adn especially Porf. Brian Kernighan, for hosting me for part of the sabbatical that gave me time to write this book.


Thanks to Cambridge University's Computer Lab, and especiall Pro.Andy Hopper, for hosting me for part fo the sabbatical that gave time to write this book.

Thansk to my deitor,Peter Gordon, and his production team at Addison-Wesley for their help and patience.

College Station,Texas     Bjarne Stroustrup




### Part I Introduction


This introduction gives an voerview of the major concepts and features of the C++ programming language and its standard library. It also provides an overivew of this book and explains the approach taken to hte description of the language facilities and their use. In addition, the intorductiory chapters present some background information about C++, the design of C++, and the use of C++.

Chapters

1 Notes to the Reader
2 A Tour of C++: The Basics
3 A Tour of C++: Abstraction Mechanisms
4 A Tour of C++: Containers and Algorithms
5 A Tour of C++: Concurrency and Utilities



