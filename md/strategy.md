# Strategy

Use strategy when you need to define a family of algorithms, encapsulate each one, and make them interchangeable.

Strategy lets the algorithm vary independently from clients that use it. 

Related patterns include State, Flyweight, Decorator, Composite.

## Diagram

![Strategy Design Pattern Diagram](/img/strategy.jpg)

## When to use?

- When you need to use one of several algorithms dynamically.

## Benefits

- Reduces multiple conditional statements in a client.

## Drawbacks

- Clients must be aware of different strategies.
