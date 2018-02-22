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
- Observer pattern defines a 1-many dependency between objects so that when one object changes state, all of its dependencies are notified and updated automatically.

**Benefit(s)**:
- Observer pattern lets you have efficient update frequencies and minimize unecessary requests for state changes.

**Resource(s)**:
- [Video](https://www.youtube.com/watch?v=_BpmfnqjgzQ)
- [Code Sample](https://github.com/evansmusomi/python3-101/blob/master/design-patterns/observer.py)
