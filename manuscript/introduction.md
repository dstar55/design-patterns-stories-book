# Introduction

## Design Patterns Stories

These days you can find tons of materials on the Internet about the Design Patterns, where patterns are mostly explained using ***Patterns Templates***. So, you start with a ***Name***, then you discuss ***Motivation***, then ***Structure***,  ***Implementation***, etc. In addition such a template, you can find lots of code examples with implementation of patterns.   

As you can see the problem isn't to find reading materials about patterns: the problem is, once you are aware of the pattern, how and where to use that pattern ?   

In this book we will tackle this problem in a different way. Each pattern will be explained using a real-life example. The real-life example will enable you to map Design Patterns using ***mind maps***. Once you map a patterns in your mind, it will be much easier to get an idea where to use it, how to combine them together, etc.   

You wake up in the morning, get dressed, go to the office. Upon entering the office building, you say hello to the security officer. Before you begin to check emails, you grab a cup of hot coffee and then you put the milk into the coffee.   

Are you aware that in the above paragraph, you touched ***Proxy***, ***Decorator*** & ***Template Method*** patterns?   

'Wake up', 'get dressed', ’go to the office' is a daily routine which is an example of the ***Template Method***. Security officer is an example of the ***Proxy***. Putting milk into one's coffee is an example of the ***Decorator***.


## Design Patterns origins: Architecture Inspires Software

Christopher Alexander, an Austrian-born architect, had a simple, elegant idea. His idea was that people should name and describe solutions to common problems in architecture. He called this concept a ‘design pattern’.
Christopher Alexander described 253 of these design patterns in his seminal book "A Pattern Language", published in 1977, that covers everything from macro to micro design. On the macro end, he describes patterns in regional and town planning, such as “Pattern 3: City Country Fingers” and “Pattern 52: Network of Paths and Cars”. In the middle of the spectrum he describes the relationship between buildings, for example “Pattern 101: Building Thoroughfare” and “Pattern 106: Positive Outdoor Space”. On the micro end he describes individual spaces and how to make them livable and delightful, using patterns such as “Pattern 159: Light on Two Sides of Every Room” and “Pattern 201: Waist High Shelf”.
Pattern 159: Light on Two Sides of Every Room 
Locate each room so that it has outdoor space outside it on at least two sides, and then place windows in these outdoor walls so that natural light falls into every room from more than one direction.
All 253 patterns when used together, in Christopher Alexander’s words, “create a coherent picture of an entire region, with the power to generate such regions in a million forms, with infinite variety in all the details”.
Moreover, a practitioner does not need to focus on all 253 patterns at once; a smaller sequence of patterns can be used as a pattern language to focus on a smaller part of the environment, say a single building or even a single room within a building.
In short, the design patterns, whether taken together or individually, articulate guidelines that can be reused for a customized design.
Fast forward a decade from the initial publication of "A Pattern Language" to 1987, when two computer scientists, Kent Beck and Ward Cunningham, inspired by the work of Christopher Alexander, began experimenting with applying the idea of design patterns to programming.
They presented their work at the OOPSLA conference (Object-Oriented Programming, Systems, Languages & Applications), subsequently sparking a new school of thought in the software engineering community.
Over the next few years these ideas gained traction, and in 1994 the Gang of Four (Erich Gamma, Richard Helm, Ralph Johnson, and John Vlissides), a group of software engineering researchers, published an influential book – "Design Patterns: Elements of Reusable Object-Oriented Software", which still lives on the bookshelves of many a software engineer (which is saying a lot for a book which is more than two decades old!).
To this day, the book is widely regarded as an important source for object-oriented design theory and practice.
The key idea of a software design pattern, like an architectural design pattern, is that it is a general reusable solution to a commonly recurring problem. It’s not a finished design that can be directly translated into code, but rather a description of how to solve a problem, which can be used in many different situations.

## Design Patterns Classification

Design Patterns are grouped into 3 categories:
* Creational
* Structural 
* Behavioral

The ***Creational*** patterns separate a system from how its objects are created, composed and represented.

* Singleton
* Abstract factory
* Factory Method
* Prototype
* Builder

The ***Structural*** patterns are used to facilitate development by identifying a simple way to realize relationships between the entities.

* Adapter
* Bridge
* Composite
* Decorator
* Facade
* Flyweight
* Proxy

The ***Behavioral*** patterns are used to provide solutions for better interaction between objects and how to provide loose coupling and flexibility to extend easily.

* Chain Of Responsibility
* Command
* Interpreter
* Iterator
* Mediator
* Memento
* Observer
* State
* Strategy
* Template Method
* Visitor
