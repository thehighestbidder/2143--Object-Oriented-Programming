# H01 - Introduction to Classes and Objects

This folder contains the work for Assignment H01, focusing on fundamental concepts of Object-Oriented Programming (OOP), specifically classes, objects, constructors, destructors, and object lifecycle management.

## Contents

* **H01\_Responses.txt**: This file contains the answers to all parts of the assignment, including:
    * Part A: Conceptual questions defining classes, objects, constructors, destructors, and the object lifecycle.
    * Part B: A minimal C++ coding example demonstrating a simple class (`Goblin`) with a private data member, a constructor, a destructor, and a public method. It also includes a brief explanation of how these elements manage the object's lifecycle.
    * Part C: Reflection and short-answer responses discussing the importance of constructors, the role of destructors (especially in languages without garbage collection), and the potential consequences of improper resource management.
* **README.md**: This file (you are currently reading it) provides an overview of the assignment and its contents.

## Assignment Overview

This assignment aimed to solidify understanding of core OOP principles:

* **Classes and Objects:** Defining the blueprint for creating objects and understanding the relationship between a class and its instances.
* **Constructors and Destructors:** Explaining the purpose of these special member functions in initializing and cleaning up objects.
* **Object Lifecycle:** Describing the stages of an object's existence from creation to destruction and the importance of resource management during this period.
* **Basic Class Design:** Demonstrating practical application of these concepts through a minimal C++ code example.

## Part A: Conceptual Questions

This section addresses the theoretical aspects of classes and objects, their creation and destruction mechanisms, and the importance of managing an object's lifespan effectively. The answers provide definitions and explanations for each concept.

## Part B: Minimal Coding Example

A simple C++ class named `Goblin` was designed to illustrate:

* **Private Data Members:** `name` (string) and `health` (integer) to represent the Goblin's attributes.
* **Constructor:** `Goblin(std::string goblinName, int initialHealth)` initializes the `name` and `health` upon object creation and prints a creation message.
* **Destructor:** `~Goblin()` is automatically called when a `Goblin` object is destroyed, printing a destruction message.
* **Public Method:** `displayState()` allows inspection of the Goblin's current `name` and `health`.

The `main` function demonstrates the creation and destruction of `Goblin` objects, highlighting the automatic invocation of constructors and destructors based on scope.

## Part C: Reflection & Short-Answer

This section provides brief reflections on the significance of constructors in ensuring valid initial object states, the necessity of destructors for resource management (especially in languages without garbage collection), and the potential problems arising from neglecting proper lifecycle management.

## Deliverables


