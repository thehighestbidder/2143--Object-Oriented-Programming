# H06 - Composition and Aggregation in OOP

This folder contains the work for Assignment H06, focusing on the concepts of composition and aggregation in Object-Oriented Programming (OOP).

## Contents

* **H06\_Responses.txt**: This file contains the answers to all parts of the assignment, including:
    * Part A: Definitions and concise examples of composition and aggregation, identification of the stronger ownership relationship, scenarios for using composition and aggregation, the difference between these "has-a" relationships and the "is-a" relationship of inheritance, and a real-world analogy illustrating both concepts.
    * Part B: A minimal C++ class example demonstrating composition with `Person` and `Address` classes, emphasizing the lifecycle dependency.
    * Part C: Reflection and short discussion on ownership and lifecycle in composition and aggregation, the advantages of composition for lifecycle control, potential pitfalls of misusing composition, and a contrast between "has-a" and "is-a" relationships, along with reasons to favor composition/aggregation over inheritance in certain scenarios.

* **README.md**: This file (you are currently reading it) provides an overview of the assignment and its contents.

## Assignment Overview

This assignment aimed to solidify understanding of:

* **Composition:** Defining a strong "has-a" relationship where one object owns and manages the lifecycle of another.
* **Aggregation:** Defining a looser "has-a" relationship where one object uses another, but the used object can exist independently.
* **Distinguishing Ownership:** Identifying the stronger form of ownership between composition and aggregation.
* **Appropriate Use Cases:** Determining scenarios where composition or aggregation is more suitable than inheritance.
* **Differences from Inheritance:** Contrasting "has-a" relationships with the "is-a" relationship of inheritance.
* **Real-World Analogies:** Relating composition and aggregation to everyday systems.
* **Minimal Class Design:** Demonstrating composition through a simple C++ class example.
* **Lifecycle Management:** Understanding how object lifecycles are affected by composition and aggregation.
* **Advantages and Pitfalls:** Considering the benefits and potential drawbacks of using composition.

## Part A: Conceptual Questions

This section addresses the theoretical aspects of composition and aggregation, providing definitions, examples, and comparisons to inheritance, along with real-world analogies to illustrate these concepts.

## Part B: Minimal Class Example

A minimal C++ code example demonstrates composition:

* **`Address` Class:** Represents a simple address with street and city.
* **`Person` Class:** Contains an `Address` object as a member, illustrating composition where the `Person` object owns and manages the `Address` object's lifecycle. The creation and destruction messages highlight this dependency.

## Part C: Reflection & Short Discussion

This section reflects on the implications of ownership and lifecycle in composition and aggregation, discusses the advantages and potential pitfalls of choosing composition, and contrasts "has-a" relationships with the "is-a" relationship of inheritance, providing reasons to favor composition or aggregation in certain design scenarios.

## Deliverables

All responses and the C++ code example are contained within the `H06_Responses` file. The C++ code is also provided directly within that text file for easy review. This `README.md` provides a summary of the assignment and its contents.
