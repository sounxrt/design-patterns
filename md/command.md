# Command

The Command pattern is used to create objects that represents actions and events in an application. A command object encapsulates an action or event and contains all information required to understand exactly what has happened. 

By passing the command object as a parameter we can, anywhereneeded extract information about occurred actions and events.

## Diagram

![Command Design Pattern Diagram](/img/command.jpg)

## When to use?

- When you want a action that can be represented in many ways. 
- To create an undo/redo functionality.

## Benefits

-  Single Responsibility Principle. You can decouple classes that invoke operations from classes that perform these operations.

## Drawbacks

- Code may become more complicated due to the introduction of new layers 
