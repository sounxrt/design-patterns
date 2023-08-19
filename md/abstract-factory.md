# Abstract Factory

The Abstract Factory pattern is a creational pattern which is related to the Factory Method pattern, but it adds another level of abstraction. 

What this means is that the pattern encapsulates a group of individual concrete factory classes (as opposed to concrete factory methods which are derived in subclasses) which share common interfaces. The client software uses the Abstract Factory which provides an interface for creating families of related
or dependent objects without specifying their concrete classes. 

This pattern separates the implementation details of a set of objects from its general usage.

## Diagram

![Abstract Factory Design Pattern Diagram](/img/abstract-factory.svg)

## When to use?

The pattern can be used where we need to create sets of objects that share a common theme and where the client only needs to know how to handle the abstract equivalence of these objects, i.e. the implementation is not important for the client. 

The Abstract Factory is often employed when there is a need to use different sets of objects and where the objects could be added or changed some time during the lifetime of an application.

## Benefits

- Use of this pattern makes it possible to interchange concrete classes without changing the code that uses them, even at runtime.

## Drawbacks

- As with similar design patterns, one of the main drawbacks is the possibility of unnecessary complexity and extra work in the initial writing of the code.
