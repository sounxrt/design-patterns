# Visitor

The visitor design pattern is a way of separating an algorithm from an object structure on which it operates. 

A practical result of this separation is the ability to add new operations to existing object structures without modifying the structures. It is one way to follow the open/closed principle.

## Diagram

![Visitor Design Pattern Diagram](/img/visitor.jpg)

## When to use?

- When you want to define new operation without changing the classes of the elements on which it operates.

## Benefits

- If the logic of operation changes, then we need to make change only in the visitor implementation rather than doing it in all the item classes.

## Drawbacks

- It makes extensions to the class hierarchy more difficult, as new classes typically require a new visit method to be added to each visitor.
