# Adapter

The Adapter pattern is used to translate the interface of one class into another interface. This means that we can make classes work together that couldn't otherwise because of incompatible interfaces. 

An object adapter relies on object aggregation.

## Diagram

![Adapter Design Pattern Diagram](/img/adapter.jpg)

## When to use?

- When you want to use an existing class, and its interface does not matchthe one you need.

## Benefits

- Introduces only one object

## Drawbacks

- When the language supports interfaces, Target must be an interface.
