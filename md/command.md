# Command

The Command pattern is used to create objects that represents actions and events in an application. A command object encapsulates an action or event and contains all information required to understand exactly what has happened. 

By passing the command object as a parameter we can, anywhereneeded extract information about occurred actions and events.

## Diagram

![Command Design Pattern Diagram](/img/command.jpg)

## When to use?

- When you want a action that can be represented in many ways. 
- To create custom action like functionaly.

## Benefits

-  A class is a suitable place to collect code and data related to a specific action or event.

## Drawbacks

- Code may become more complicated due to the introduction of new layers 
