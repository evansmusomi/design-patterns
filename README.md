# Design Patterns

Resources to help you understand common design patterns. With examples.

### 1. Strategy Pattern

**Gist**: 
- Composition is preferable to inheritance for code re-use.
- Strategy pattern defines a family of algorithms, encapsulates each one, and makes them interchangeable.

**Benefit(s)**: 
- Strategy lets the algorithm vary independently from clients that use it (decoupling).

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=v9ejT8FO-7I)
- [Code Sample](https://github.com/evansmusomi/python3-101/blob/master/design-patterns/strategy.py)

### 2. Observer Pattern

**Gist**: 
- Prefer push (or push and pull) to poll architecture for state maintenance between observables and observers.
- Observer pattern defines a 1-to-many dependency between objects so that when one object changes state, all of its dependencies are notified and updated automatically.

**Benefit(s)**:
- Observer pattern lets you achieve more efficient update frequencies and minimize unnecessary requests for state changes.

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=_BpmfnqjgzQ)
- [Code Sample](https://github.com/evansmusomi/python3-101/blob/master/design-patterns/observer.py)

### 3. Decorator Pattern

**Gist**:
- Change the behaviour of an object or component at run time without changing the content of the object itself, by wrapping it with another object.
- Decorator pattern attaches additional responsibility to an object or function, dynamically.
- In terms of relationship, decorators define an *is a* and *has a* relationship with the component they wrap.

**Benefit(s)**:
- Decorator pattern provides a flexible alternative to sub-classing when extended functionality is desired.
- You can use a single decorator or series of decorators to extend functionality of a concrete object or function at run-time.

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=GCraGHx6gso)
- [Code Sample](https://github.com/evansmusomi/python3-101/blob/master/design-patterns/decorator.py)

### 4. Factory Method Pattern

**Gist**:
- Factory pattern defines an interface for creating an object but lets sub-classes decide which class to instantiate.

**Benefit(s)**:
- Allows encapsulation of logic around creation of objects for uniform instantiation of classes across the program and to enable polymorphism.

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=EcFVTgRHJLM)
- [Code Sample](https://github.com/evansmusomi/python3-101/blob/master/design-patterns/factory.py)

### 5. Abstract Factory Pattern

**Gist**:
- Abstract factory pattern provides an interface for creating a family of related or dependent objects without specifying their concrete classes.

**Benefit(s)**:
- Returns multiple objects (or factory methods).

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=v-GiuMmsXj4)
- [Code Sample](https://github.com/evansmusomi/python3-101/blob/master/design-patterns/abstract_factory.py)

### 6. Singleton Pattern

**Gist**:
- Singleton pattern ensures a class has only one instance and provides global access to it.

**Benefit(s)**:
- *Use of this pattern is cautioned against*. However, if you're sure you'll never need more than one instance of a class, the pattern helps you achieve that.

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=hUE_j6q0LTQ)
- [Code Sample](https://github.com/evansmusomi/python3-101/blob/master/design-patterns/singleton.py)

### 7. Command Pattern

**Gist**:
- Wrap the action you want to perform in a particular command and make sure that action is undoable.
- Command pattern encapsulates a request (command object), thereby letting you parameterize other objects with different requests, queue or log requests and support undoable operations.

**Benefit(s)**:
- Enables undo operations.
- Enables you to construct macro-commands (commands with multiple commands).

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=9qA5kw8dcSU)

### 8. Adapter Pattern

**Gist**:
- Create a wrapper that facilitates interoperability between two interfaces. _No functionality is added or removed_.
- Adapter pattern converts the interface of a class into another interface the client expects.

**Benefit(s)**:
- Enables you to make interfaces compatible.
- Adapters let classes work together that couldn't otherwise because of incompatible interfaces.

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=2PKQtcJjYvc)
- [Code Sample](https://github.com/evansmusomi/python3-101/blob/master/design-patterns/adapter.py)

### 9. Facade Pattern

**Gist**:
- Give clients a simple interface to interact with that abstracts the complexity of the underlying system.
- Facade pattern provides a uniform interface to a set of interfaces in a sub-system.

**Benefit(s)**:
- Simplifies interaction with complex systems by providing a higher level interface that makes sub-systems easier to use.

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=K4FkHVO5iac)
