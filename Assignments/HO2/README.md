# H02 - Encapsulation and Visibility in OOP

This folder contains the work for Assignment H02, focusing on the concept of encapsulation and visibility modifiers in Object-Oriented Programming (OOP).

## Contents

* **H02\_Responses.txt**: This file contains the answers to all parts of the assignment, including:
    * Part A: Definitions and explanations of encapsulation, public, private, and protected access modifiers, their benefits and drawbacks, and the impact of encapsulation on code maintenance. It also includes a real-world analogy.
    * Part B: A minimal C++ class design for `BankAccount`, demonstrating private data members (`balance`, `accountNumber`) and public methods (`deposit`, `withdraw`). It provides justifications for the visibility choices and conceptual documentation.
    * Part C: Reflection and short-answer responses discussing the pros and cons of hiding internal data, the difference between encapsulation and abstraction, their relationship to information hiding, and strategies for testing encapsulated classes.
* **README.md**: This file (you are currently reading it) provides an overview of the assignment and its contents.

## Assignment Overview

This assignment aimed to solidify understanding of:

* **Encapsulation:** Defining the concept of bundling data and methods and controlling access to data to prevent unintended changes.
* **Visibility Modifiers:** Comparing and contrasting `public`, `private`, and `protected` access in terms of flexibility, safety, and maintainability, and identifying scenarios for their intentional use.
* **Impact on Maintenance:** Explaining how encapsulation contributes to reduced debugging complexity and providing an example of potential issues with public internal data.
* **Real-World Analogy:** Relating the concepts of public interface and private implementation to a familiar object.
* **Small Class Design:** Structuring a minimal C++ class (`BankAccount`) with appropriate visibility modifiers and demonstrating how public methods enforce constraints on private data.
* **Testing Encapsulated Classes:** Proposing a strategy for thoroughly unit testing classes with private data.

## Part A: Conceptual Questions

This section addresses the theoretical aspects of encapsulation and visibility, providing definitions, comparisons, and examples to illustrate these fundamental OOP principles.

## Part B: Small-Class Design (Minimal Coding)

A simple C++ class named `BankAccount` was outlined to demonstrate:

* **Private Data Members:** `balance` (double) and `accountNumber` (string) to represent the account's internal state.
* **Public Methods:** `deposit(double amount)` and `withdraw(double amount)` to provide controlled ways to interact with the `balance`.
* **Encapsulation Justification:** Explanations for why `balance` and `accountNumber` should be private.
* **Constraint Enforcement:** Descriptions of how `deposit` and `withdraw` methods validate input before modifying the `balance`.
* **Documentation:** Conceptual demonstration of how to document the class to guide other developers on proper usage.

## Part C: Reflection & Short-Answer

This section provides reflections on the advantages and disadvantages of encapsulation, the distinction between encapsulation and abstraction, their role in information hiding, and a strategy for effectively testing encapsulated classes through their public interface.

## Deliverables

All responses and the C++ class outline are contained within the `H02_Responses.txt` file. The C++ code snippets are also included directly within that text file for easy review. This `README.md` provides a summary of the assignment and its contents.
