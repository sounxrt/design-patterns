# Visitor

The visitor design pattern is a way of separating an algorithm from an object structure on which it operates. 

A practical result of this separation is the ability to add new operations to existing object structures without modifying the structures. It is one way to follow the open/closed principle.

In essence, the visitor allows **adding new virtual functions to a family of classes, without modifying the classes**. Instead, a visitor class is created that implements all of the appropriate specializations of the virtual function. The visitor takes the instance reference as input, and implements the goal through double dispatch.

## Diagram

![Visitor Design Pattern Diagram](/img/visitor.jpg)

## When to use?

- When you want to define a new operation for (some) classes of an object structure without changing the classes.
- Many unrelated operations on an object structure are required.

## Benefits

- If the logic of operation changes, then we need to make change only in the visitor implementation rather than doing it in all the item classes.
- Useful when new operations need to be added frequently.

## Drawbacks

- It makes extensions to the class hierarchy more difficult, as new classes typically require a new visit method to be added to each visitor.
