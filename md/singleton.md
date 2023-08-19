# Singleton

The Singleton pattern provides the possibility to control the number of instances (mostly one) that are allowed to be made. We also receive a global point of access to it (them).

## Diagram

![Singleton Design Pattern Diagram](/img/singleton.svg)

## When to use?

- When only one instance or a specific number of instances of a class are allowed. Facade objects are often Singletons because only one Facade object is required.

## Benefits

- Controlled access to unique instance.
- Reduced name space.
- Allows refinement of operations and representations.

## Drawbacks

- Singleton pattern is also considered an anti-pattern by some people, who feel that it is overused, introducing unnecessary limitations in situations where a sole instance of a class is not actually required.
