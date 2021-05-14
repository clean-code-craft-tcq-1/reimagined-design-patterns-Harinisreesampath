# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.

# Adapter Pattern

**Basic Idea:**
It’s about getting the interface that you want from the interface that you were given by some system. So, the typical representation of an adapter is just the same as we have in the electrical devices, where we have different power requirements. In short, an existing interface X adapts to the required interface Y.

**Usage:**
When our application is not compatible with the interface that the client is expecting.

**Example:**
Electrical devices have different power(interface) requirements. We cannot modify our gadgets to support every possible interface. Thus, we use a special device (an adapter) to give us the interface we require from the interface we have.

**Advantages:**
•	Reusability and flexibility.

**Disadvantages:**
•	In some cases, it forms a chain of adaptations to reach the required type. Hence resulting in complexity.

# Composite Pattern

**Basic Idea:**
It allows us to treat individual or aggregate objects uniformly. A mechanism for treating individual objects and compositions of objects in a same manner.

**Usage:**
It should be used when multiple objects are handled in the same manner, then composite pattern can be used. 

**Example:**
In any drawing application like PowerPoint, we know that in addition to having several different shapes separately we can take several shapes and group them together and track them as a group.

**Advantages:**
•	Less memory usage due to a smaller number of objects.

**Disadvantages:**
•	When you don’t want to represent a full hierarchy of objects.

# Memento Pattern

**Basic Idea:**
Memento is to keep some sort of token which then allows you to return an object to a particular state.

**Usage:**
An object or system goes through changes. Memento Design Pattern will be used in situations where some actions are undoable, therefore requiring to roll back to a previous state.

**Example:**
A text editor with save and undo functions.

**Advantages:**
•	Provides a recovery mechanism in case of failures.

**Disadvantages:**
•	Increased use of memory.

# Mediator Pattern

**Basic Idea:**
It provides the communication between components by letting the components be aware of each other’s presence or absence in the system.

**Usage:**
It can be used when we have a set of objects that are tightly coupled.

**Example:**
Players in some online game. It makes no sense for the players to have direct references to one another because they can go at any time.

**Advantages:**
•	Easy communication between objects.

**Disadvantages:**
•	Too much logic in mediator may end up in God class.
