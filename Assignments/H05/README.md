# H05 - Abstraction in Object-Oriented Programming

This folder contains the work for Assignment H05, focusing on the concept of abstraction in Object-Oriented Programming (OOP).

## Contents

* **H05\_Responses.txt**: This file contains the answers to all parts of the assignment, including:
    * Part A: Definition of abstraction, a real-world analogy, comparison with encapsulation, reasons for potential confusion, designing with abstraction (smart thermostat example), and benefits of abstraction.
    * Part B: A minimal C++ class example modeling a banking system with an abstract `BankAccount` class and a concrete `SavingsAccount` derived class, demonstrating the hiding of internal complexities.
    * Part C: Reflection and comparison, discussing which data/methods to hide in `SavingsAccount`, the interplay of abstraction and polymorphism, and another real-world domain where abstraction is crucial.

* **README.md**: This file (you are currently reading it) provides an overview of the assignment and its contents.

## Assignment Overview

This assignment aimed to solidify understanding of:

* **Abstraction:** Defining the process of simplifying complex systems by focusing on essential features and hiding unnecessary details.
* **Abstraction vs. Encapsulation:** Differentiating these related concepts in information hiding.
* **Designing with Abstraction:** Applying abstraction principles to model a real-world system (smart thermostat).
* **Benefits of Abstraction:** Recognizing the advantages of abstraction in large-scale software development.
* **Minimal Class Example:** Demonstrating abstraction through a C++ banking system model with an abstract base class.
* **Reflection and Comparison:** Analyzing how abstraction is applied in the provided example and its relationship with polymorphism, along with identifying other real-world applications of abstraction.

## Part A: Conceptual Questions

This section addresses the theoretical aspects of abstraction, providing a definition, analogy, comparison with encapsulation, and exploring its benefits in software design through a practical example.

## Part B: Minimal Class Example

A minimal C++ code example demonstrates abstraction in a banking system:

* **Abstract Base Class (`BankAccount`):** Defines a contract for bank accounts with pure virtual methods (`deposit`, `withdraw`, `getBalance`).
* **Derived Class (`SavingsAccount`):** Inherits from `BankAccount` and provides concrete implementations for the abstract methods, while hiding internal details like transaction logging and fund checking.

## Part C: Reflection & Comparison

This section reflects on the implementation choices in the `SavingsAccount` class regarding information hiding, explores the interplay between abstraction and polymorphism in the context of the example, and identifies another real-world domain where abstraction plays a vital role in simplifying complex systems.

## Deliverables

All responses and the C++ code example are contained within the `H05_Responses` file. The C++ code is also provided directly within that text file for easy review. This `README.md` provides a summary of the assignment and its contents.
