---
layout: post
title: SOLID Design Principles Explained
featured-img: Data_Structure

---
## What is SOLID Design Principles?
The term SOLID is an acronym that describes the five design principles that makes our software more understandable for our users to grasp. It is one of the most popular design principles in an object-oriented software development environment. It allows many developers to write and program their code more organized, flexible, and straight forward without losing any integrity or maintainability in design.

There are five design principles to know:

![image tooltip here](/assets/img/SOLID.jpg)

## S-Single Responsibility Principle
With Single Responsibility Principle, a class within the code should have only one responsibility that can be entirely encapsulated by the class. Its principle is to states that every module or class should have some sort of responsibility over a single part of the functionality provided by the software.

## O-Open-Closed Principle
In a typical object-oriented programming environment, the open/closed principle states that any software entitles such as classes, modules, or functions should be open for extension, but closed for modification. In layman's term, the software entity can allow its behavior to be extended without modifying its algorithm in the source code.

## I-Liskov Substitution Principle
The Liskov Substitution Principle (LSP) is a principle that functions in order to use pointers to base classes in order to be able to use objects of derived classes without knowing it. In layman's terms, some language that sounds right in natural language doesn't quite work in code. For a mathematical example think a square to a rectangle as equivalent, however the code you made Square derive from rectangle thus square can be usable anywhere you expected. This demonstrates as some strange behavior.

![image tooltip here](/assets/img/lsp.jpg)

## Interface Segregation Principle
Interface-segregation principle (ISP) states that no client should be forced to depend on methods it does not use. ISP splits interfaces that are very large into a smaller and more specific ones sot that clients will know about the methods that are very interested to them.


## Dependency Inversion
Dependency Inversion Principle refers to a specific form of decoupling software modules. It states that high level modules should not depend on low level modules, thus both should depend on abstractions. It is common when writing a code for a software, it is important to implement to lower level modules to suffice the abstractions.
