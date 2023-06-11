# Chain of Responsability

The Chain-of-responsibility pattern lets more than one object handle a request without mutual knowledge. 

We avoid coupling between the sender of a request and the possible receivers. We place all receivers in a chain which lets the receiving objects pass the request along to the next receiver in the chain until one receiver handles it, or the end of the chain is reached.

## Diagram

![Chain of Responsability Design Pattern Diagram](/img/chain-of-responsability.jpg)

## When to use?

 - When more than one object may handle a request, and the handler isn't known.
 - When you want to issue a request to one of several objects without specifying the receiver explicitly.
 - When the set of objects that can handle a request should be specified dynamically.

## Benefits

- It reduces coupling.
- It increases the flexibility of handling a request.

## Drawbacks

- Reception isn't guaranteed since a request has no explicit receiver, there's no guarantee it will be handled unless the chain is configured properly.
