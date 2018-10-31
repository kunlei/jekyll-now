---
layout: post
title: Command Pattern
---

**Command Pattern** is one of the behavioral design patterns that consists of four essential components:
- Command: this is essentially an interface to be implemented by concrete classes. It decouples the invoker which is the user of various methods provided by receivers, so instead of a invoker directly calling methods provided by receivers, invokers call a common interface. An example of this pattern can be seen in the Runnable interface provided by JDK.
- Receiver: this is the concrete classes that define specific behaviors conforming to the method defined by the Command interface. 
- Invoker: this is the user of the Command interface.
- Client: this control the initialization of receivers and invokers.

