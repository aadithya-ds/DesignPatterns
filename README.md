# Design Pattern


A design pattern is a reusable solution to a commonly occurring problem in software design. It provides a standard way to structure your code to solve specific problems effectively. Design patterns are not code themselves but are guidelines or templates that help developers write better, more maintainable, and more flexible software.

## Behavioral design pattern

Behavioral patterns focus on how objects interact with each other and how responsibilities are distributed among them. These patterns improve communication and make the system more flexible by allowing objects to change their behavior at runtime.



## Key Characteristics of Behavioral Patterns

* Define clear communication protocols between objects.
* Separate the responsibility for performing an action from the object triggering the action.
* Often involve delegation and polymorphism.


## Strategy Pattern

* The Strategy Pattern is a behavioral design pattern that allows you to define a family of algorithms (strategies), encapsulate each algorithm in its own class, and make them interchangeable at runtime.

* It’s like having different tools to perform the same task, where you can switch tools without changing the task itself.

## Key Components of the Strategy Pattern
### Strategy Interface:
* Defines a common method that all strategies must implement.
Ensures consistency among different strategies.

### Concrete Strategies:
* Implement specific versions of the algorithm.
Each strategy encapsulates one way of solving a problem.

### Context Class:
* Maintains a reference to a strategy object.
Delegates the algorithm execution to the selected strategy.

## When to Use the Strategy Pattern?
- When you have multiple algorithms or behaviors for a task, and the choice of algorithm can change dynamically.
To avoid large conditional (if-else or switch) statements in the code.
To make the system extensible by adding new behaviors without altering existing code.

### Example: Payment System
* Let’s use the Strategy Pattern to create a payment system where users can choose different payment methods (e.g., Credit Card, PayPal, Bank Transfer).
