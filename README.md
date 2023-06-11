
# Design Patterns

## Behavioral Design Patterns

Design patterns that identify common **communication** patterns between objects and realize these patterns. 

Behavioral patterns are patterns that focuses on the interactions between cooperating objects. The interactions between cooperating objects should be such that they are communicating while maintaining as loose coupling as possible. 

The loose coupling is the key to n-tier architectures. 

| Name                                                      | Description                                                                                                                                                                                             |
|-----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Chain of Responsability](/md/chain-of-responsability.md) | The Chain-of-responsibility pattern lets more than one object handle a request without mutual knowledge.                                                                                                |
| [Command](/md/command.md)                                 | The Command pattern is used to create objects that represents actions and events in an application.                                                                                                     |
| Iterator                                                  | The Iterator design pattern provides a way to access the elements of an aggregate object sequentially without exposing its underlying representation.                                                   |
| [Mediator](/md/mediator.md)                               | Objects no longer communicate directly with each other, but instead communicate through the mediator.                                                                                                   |
| Memento                                                   | To record an object internal state without violating encapsulation and reclaim it later without knowledge of the original object.                                                                       |
| Observer                                                  | An observer is a structural pattern that enables publish/subscribe functionality.                                                                                                                       |
| State                                                     | The State pattern allows an object to alter its behavior when its internal state changes.                                                                                                               |
| [Strategy](/md/strategy.md)                               | Use strategy when you need to define a family of algorithms, encapsulate each one, and make them interchangeable.                                                                                       |
| Template Method                                           | Template Method is a behavioral design pattern that defines the skeleton of an algorithm in the superclass but lets subclasses override specific steps of the algorithm without changing its structure. |
| [Visitor](/md/visitor.md)                                 | Visitor is a behavioral design pattern that lets you separate algorithms from the objects on which they operate.                                                                                        |

## Creational Design Patterns

Creational design patterns are design patterns that deal with **object creation** mechanisms.

The basic form of object creation could result in design problemsor added complexity to the design. Hard coding the actual instantiation is a pitfall and should be avoided if reuse and changeability are desired.

| Name             | Description                                                                                                                                                                        |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Abstract Factory | The pattern encapsulates a group of individual concrete factory classes (as opposed to concrete factory methods which are derived in subclasses) which share common interfaces.    |
| Builder          | The Builder pattern can be used to ease the construction of a complex object from simple objects.                                                                                  |
| Factory          | The Factory pattern provides a way to use an instance as a object factory.                                                                                                         |
| Prototype        | The Prototype pattern is basically the creation of new instances through cloning existing instances.                                                                               |
| Singleton        | The Singleton pattern provides the possibility to control the number of instances (mostly one) that are allowed to be made. We also receive a global point of access to it (them). |

## Structural Design Patterns

Design patterns that ease the design by identifying a simple way to realize **relationships** among entities (objects and classes). 

| Name                          | Description                                                                                                                                         |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| [Adapter](/md/adapter.md)     | Translates the interface of one class into another interface.                                                                                       |
| [Bridge](/md/bridge.md)       | Used to decouple the interfaces from implementation and hiding the implementation details from the client program.                                  |
| [Composite](/md/composite.md) | Helps you to create treee structures of objects without the need to force clients to differentialte between brances and leaves regarding usage.     |
| [Decorator](/md/decorator.md) | Lets you attach additional responsibilities and modify an instance functionality dynamically.                                                       |
| [Facade](/md/facade.md)       | Provides a unified interface to a set of interfaces in a subsystem.                                                                                 |
| [Flyweight](/md/flyweight.md)    | Provides a mechanism by which you can avoid creating a large number of expensive objects and instead reuse existing instance to represent new ones. |
| [Proxy](/md/proxy.md)                         | Provide a surrogate or placeholder for another object to control access to it.                                                                      |

## Reference

- Design Patterns Explained with Java and UML2
- https://refactoring.guru/design-patterns/
- https://www.digitalocean.com/community/tutorials/gangs-of-four-gof-design-patterns
- [Wikipedia](https://en.wikipedia.org/)
