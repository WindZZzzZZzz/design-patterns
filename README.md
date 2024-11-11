# Design Patterns Repository

Welcome to the **Design Patterns** repository!

This repository is a collection of commonly used design patterns implemented in JAVA languages.

## Creational Design Patterns
Creational patterns focus on object creation mechanisms, trying to create objects in a manner suitable to the situation.

1. **Singleton**  
   Ensures a class has only one instance and provides a global point of access to it.

2. **Factory Method**  
   Defines an interface for creating objects, but allows subclasses to alter the type of objects that will be created.

3. **Abstract Factory**  
   Provides an interface for creating families of related or dependent objects without specifying their concrete classes.

4. **Builder**  
   Allows the construction of a complex object step by step. The construction process can create different representations of the object.

5. **Prototype**  
   Specifies the kinds of objects to create using a prototypical instance and creates new objects by copying this prototype.

---

## Structural Design Patterns
Structural patterns focus on simplifying the design by identifying simple ways to realize relationships between entities.

1. **Adapter**  
   Converts one interface to another expected by the client, allowing classes to work together that couldn’t otherwise.

2. **Bridge**  
   Decouples an abstraction from its implementation so that both can vary independently.

3. **Composite**  
   Allows you to compose objects into tree structures to represent part-whole hierarchies. It lets clients treat individual objects and compositions of objects uniformly.

4. **Decorator**  
   Adds additional responsibilities to an object dynamically. A flexible alternative to subclassing for extending functionality.

5. **Facade**  
   Provides a simplified interface to a complex subsystem, making it easier to use by abstracting away the complexities.

6. **Flyweight**  
   Reduces the memory usage by sharing common parts of the state between multiple objects, particularly useful when many objects of a similar type are needed.

7. **Proxy**  
   Provides a surrogate or placeholder for another object, controlling access to it and potentially adding additional functionality like lazy initialization or access control.

---

## Behavioral Design Patterns
Behavioral patterns focus on communication between objects, what goes on between objects and how they operate together.

1. **Chain of Responsibility**  
   Passes a request along a chain of handlers. Each handler processes the request or passes it along to the next handler in the chain.

2. **Command**  
   Encapsulates a request as an object, allowing for parameterization of clients with queues, requests, and operations.

3. **Interpreter**  
   Defines a grammatical representation for a language and an interpreter that uses the representation to interpret sentences in the language.

4. **Iterator**  
   Provides a way to access the elements of an aggregate object sequentially without exposing its underlying representation.

5. **Mediator**  
   Defines an object that encapsulates how a set of objects interact, reducing the dependency between communicating objects.

6. **Memento**  
   Captures and externalizes an object’s internal state so that the object can be restored to this state later.

7. **Observer**  
   Allows a subject to notify its observers when there is a change in its state. Commonly used for event-driven systems.

8. **State**  
   Allows an object to alter its behavior when its internal state changes. The object will appear to change its class.

9. **Strategy**  
   Defines a family of algorithms, encapsulates each one, and makes them interchangeable. Strategy lets the algorithm vary independently from clients that use it.

10. **Template Method**  
    Defines the skeleton of an algorithm, deferring some steps to subclasses. Subclasses can redefine certain steps of the algorithm without changing its structure.

11. **Visitor**  
    Represents an operation to be performed on elements of an object structure. A way to separate algorithms from the objects on which they operate.

---
