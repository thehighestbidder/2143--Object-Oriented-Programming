# H03 - Inheritance in Object-Oriented Programming

This folder contains the work for Assignment H03, focusing on the concept of inheritance in Object-Oriented Programming (OOP).

## Contents

* **H03\_Responses.txt**: This file contains the answers to all parts of the assignment, including:
    * Part A: Definition of inheritance, its difference from composition and aggregation, explanations of single and multiple inheritance with examples, the purpose of method overriding, and a real-world analogy.
    * Part B: A minimal C++ coding example demonstrating inheritance with a `Vehicle` base class and a `Car` derived class, showcasing method overriding. It also includes a brief explanation of the code.
    * Part C: Short reflection and discussion on when to use inheritance, the difference between method overriding and overloading, the importance of overriding in inheritance, and the distinction between inheritance and interfaces/abstract classes, along with a potential pitfall of multiple inheritance and a mitigation strategy.
* **README.md**: This file (you are currently reading it) provides an overview of the assignment and its contents.

## Assignment Overview

This assignment aimed to solidify understanding of:

* **Inheritance:** Defining the mechanism of inheriting properties and behaviors from a base class to a derived class.
* **Composition and Aggregation:** Differentiating inheritance from other ways of creating complex objects.
* **Types of Inheritance:** Understanding single and multiple inheritance with practical scenarios.
* **Overriding Methods:** Explaining how derived classes can customize inherited functionality.
* **Real-World Analogy:** Relating the concept of inheritance to everyday objects or systems.
* **Minimal Coding Example:** Demonstrating inheritance and method overriding in C++.
* **Reflection and Discussion:** Considering the appropriate use cases for inheritance, the difference between overriding and overloading, and the relationship between inheritance and interfaces/abstract classes, along with the challenges of multiple inheritance.

## Part A: Conceptual Questions

This section addresses the theoretical aspects of inheritance, providing definitions, comparisons, and examples to illustrate this key OOP principle.

## Part B: Minimal Coding Example

A simple C++ code example demonstrates:

* **Base Class (`Vehicle`):** Contains a `brand` attribute and a generic `drive()` method.
* **Derived Class (`Car`):** Inherits from `Vehicle`, adds a `doors` attribute, and overrides the `drive()` method to provide car-specific behavior.
* **Driver Code:** Shows how to create objects of both `Vehicle` and `Car` and call the `drive()` method to observe the polymorphic behavior.

## Part C: Short Reflection & Discussion

This section provides reflections on the appropriate use of inheritance, the distinction between method overriding and overloading, the importance of overriding in the context of inheritance, and a discussion comparing inheritance with interfaces and abstract classes, including a consideration of the pitfalls of multiple inheritance and potential solutions.

## Deliverables

All responses and the C++ code example are contained within the `H03_Responses.txt` file. The C++ code is also provided directly within that text file for easy review. This `README.md` provides a summary of the assignment and its contents.
