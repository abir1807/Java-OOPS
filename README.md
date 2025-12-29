# Java-OOPS
Object Oriented Programming concepts in Java with examples.

This repository contains clean, well-structured Java programs demonstrating all core Object-Oriented Programming (OOP) concepts.
The examples are designed to be simple, readable, and exam/interview-friendly, focusing on conceptual clarity rather than complexity.

# Abstraction

Abstraction is demonstrated using abstract classes where implementation details are hidden and only essential behavior is exposed.

Key Features:
->Abstract methods
->Concrete methods inside abstract classes
->Runtime polymorphism through abstraction

Examples:
->Shape Example – abstract area() method implemented by Circle and Rectangle
->Food Ordering System – abstract prepareFood() with common deliverFood() behavior

# Encapsulation

Encapsulation is achieved by hiding data using private variables and providing controlled access through methods.

Key Features:
->Private data members
->Getters and setters for simple fields
->Business logic methods for sensitive data (no direct setters)

Examples:
->Student Class – basic encapsulation with validation
->Bank Account Management – strong encapsulation using deposit/withdraw methods instead of direct balance setters

# Polymorphism

Polymorphism allows the same method name to behave differently based on context.
Both compile-time and runtime polymorphism are demonstrated.
  1)Compile-Time Polymorphism (Method Overloading)

Compile-time polymorphism is achieved using method overloading, where multiple methods share the same name but differ in parameters.
Key Features:
-> Same method name
-> Different number or type of parameters
-> Method call resolved at compile time
Examples:
-> Calculator Class – overloaded add() methods

  2)Runtime Polymorphism (Method Overriding)

Runtime polymorphism is achieved using inheritance and method overriding.
Key Features:
-> Method overriding
-> Parent class reference pointing to child object
-> Method call resolved at runtime

Examples:
-> Animal Example – sound() method overridden by Dog and Cat classes

# inheritance

Inheritance allows a class to acquire properties and behaviors of another class.
Different types of inheritance supported by Java are demonstrated.

  1)Single Inheritance
A single child class inherits from a single parent class.
Examples:
-> Vehicle → Car

  2)Multilevel Inheritance
A class is derived from another derived class, forming multiple levels.
Examples:
-> AEC → CSE → ThirdYear

Hierarchical Inheritance
  3)Multiple child classes inherit from a single parent class.

Examples:
-> Mobile → Samsung
-> Mobile → Apple

  4)Multiple Inheritance (Using Interfaces)

Java does not support multiple inheritance using classes, but it supports it using interfaces.

Key Features:
-> Multiple interfaces implemented by a single class
-> Avoids diamond problem
-> Clean and flexible design

Examples:
-> LandVehicle + WaterVehicle → AmphibiousVehicle
