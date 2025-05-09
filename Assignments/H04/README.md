# H04 - Polymorphism in Object-Oriented Programming

This folder contains the work for Assignment H04, focusing on the concept of polymorphism in Object-Oriented Programming (OOP).

## Contents

* **H04\_Responses.txt**: This file contains the answers to all parts of the assignment, including:
    * Part A: Definition of polymorphism, its importance as a pillar of OOP, explanations of compile-time (overloading) and runtime (overriding) polymorphism, the necessity of inheritance for runtime polymorphism, the purpose and example of method overloading, and the mechanism and need for the `virtual` keyword/annotations in method overriding.
    * Part B: A minimal pseudo-code demonstration illustrating runtime polymorphism with a `Shape` base class and `Circle` and `Rectangle` derived classes, showcasing the dynamic dispatch of the `draw()` method.
    * Part C: Distinctions between method overloading and overriding, explaining compile-time resolution for overloading and runtime resolution for overriding, and the significance of runtime polymorphism for flexible code design.

* **README.md**: This file (you are currently reading it) provides an overview of the assignment and its contents.

## Assignment Overview

This assignment aimed to solidify understanding of:

* **Polymorphism:** Defining the ability of objects of different classes to respond uniquely to the same method call.
* **Importance of Polymorphism:** Recognizing its role in promoting flexibility, extensibility, and code reusability in OOP.
* **Compile-Time vs. Runtime Polymorphism:** Differentiating between method overloading (resolved at compile time) and method overriding (resolved at runtime).
* **Method Overloading:** Understanding its purpose in providing multiple ways to perform similar operations.
* **Method Overriding:** Describing how derived classes specialize base class behavior.
* **Minimal Demonstration:** Illustrating runtime polymorphism through a simple pseudo-code example.
* **Overloading vs. Overriding Distinctions:** Clarifying when the decision for method invocation occurs in each type and why runtime polymorphism is crucial for flexible design.

## Part A: Conceptual Questions

This section addresses the theoretical aspects of polymorphism, providing definitions, comparisons, and examples to illustrate its core principles and benefits in OOP.

## Part B: Minimal Demonstration

A minimal pseudo-code example demonstrates runtime polymorphism:

* **Base Class (`Shape`):** Defines a `virtual` `draw()` method.
* **Derived Classes (`Circle`, `Rectangle`):** Inherit from `Shape` and override the `draw()` method to print shape-specific drawing actions.
* **Demonstration:** Shows how a list of `Shape` references can hold objects of `Circle` and `Rectangle`, and calling `draw()` on each invokes the correct overridden method at runtime.

## Part C: Overloading vs. Overriding Distinctions

This section clarifies the key differences between method overloading (compile-time polymorphism) and method overriding (runtime polymorphism), emphasizing when the method call resolution occurs and why runtime polymorphism is essential for achieving flexible and extensible object-oriented designs.

## Deliverables

All responses and the pseudo-code demonstration are contained within the `H04_Responses.txt` file. The pseudo-code is also provided directly within that text file for easy review. This `README.md` provides a summary of the assignment and its contents.
