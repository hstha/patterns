# Behavioral Design Pattern

Behavioral design pattern focus on improving communication between objects. It plays an important role in facilitating clear and effective communication between objects, making the systems easier to understand and manage. They focus on the responsibilities of objects and how they communicate, which helps reduce tight coupling.

It deal with the communication or interaction between Classes and Objects. This ensures that the communication is carried out effectively while keeping the coupling loose. The primary goal of these patterns is ti enhance the communication between objects, making it more flexible and efficient.

It describes how different objects and classes send messages to each other to make things happen and how the steps of a task are divided among different objects.

Behavioral design patterns are concerned with algorithms and the assignment of responsibilities between objects.

## Benefits of behavioral design patterns

- **Improved Handling of Interactions**: By focusing on effective communication and responsibility delegation, these patterns improve the handling of complex interactions.

- **Increased Modularity**: Encouraging fine-grained and decoupled object interactions leads to more modular code.

- **Dynamic Control**: Many behavioral patterns, such as State and Strategy, allow for changes in software's behavior in runtime, making it more dynamic and responsive.

## When to use behavioral design patterns

- **Flexibility in Interaction**: These provide greater flexibility in deciding how objects interact with each other.

- **Ease of Maintenance**: Encapsulating behavior in objects or classes that can be easily modified independently enhances maintainability.

- **Enhanced Control Flow**: They can improve the control flow between objects and manage complex conditions more effectively.

## Types of behavioral design patterns

1. **Chain of Responsibility**: The chain of responsibility design pattern allows an object to send commands without knowing which object will receive and handle them. Requests are passed along a chain of potential handlers until one of them deals with the request. It lets you pass requests along a chain of handlers. Upon receiving a request, each handler decides either to process the request or to pass it to the next handler in the chain.

2. **Command Pattern**: The command design pattern turns a request into a stand-alone object containing all the requested information. This transformation allows command execution to be parameterized with different requests, queues, or log operations and supports undoable operations. For example, GUI buttons. Each button has a command associated with it. When the button is pressed, its command is executed.

3. **Interpreter Pattern**: The interpreter design pattern is used to design a component that interprets programs written in a dedicated language.

4. **Iterator Pattern**: The iterator design pattern provides a way to access the elements of an aggregate object sequentially without exposing its underlying representation. It lets you traverse elements of collection without exposing its underlying representation (list, stack, tree, etc)

5. **Mediator Pattern**: The mediator pattern reduces the dependencies between objects by making them communicate indirectly though a specially designed mediator object. it reduce chaotic dependencies between objects, restricting the direct communications between the objects and forces them to collaborate only via a mediator object.

6. **Memento Pattern**: The memento design pattern captures and externalizes an object's internal state  so that it can be restored later, all without violating encapsulation. It lets you save and restore the previous state of an object without revealing the details of its implementation.

7. **Observer Pattern**: The observer design pattern allows several observer objects to see an event and respond to it. It lets you define a subscription mechanism to notify multiple objects about any events that happen to the object they're observing.

8. **State Pattern**: The state design pattern allows an object to alter its behavior when its internal state changes. It lets an object alter its behavior when its internal state changes. It appears as if the object changed it class.

9. **Strategy Pattern**: The strategy design pattern defines a family of algorithms, encapsulates each one, and makes them interchangeable. It lets the algorithm vary independently form the clients that use it. It lets you define a family of algorithms, put each of them into a separate class, and make their objects interchangeable.

10. **Template Method Pattern**: The template method design pattern defines the skeleton of an algorithm in the superclass but lets subclasses override specific steps of the algorithm without changing its structure. It defines the skeleton of an algorithm in the superclass but lets subclasses override specific steps of the algorithm without changing its structure.

11. **Visitor Pattern**: The visitor design pattern lets you define a new operation without changing the classes of the elements on which it operates. It lets you separate algorithms from the objects on which they operate.

## References

- [Refactor Guru](https://refactoring.guru/design-patterns/behavioral-patterns)
- [Dot Net Tutorials](https://dotnettutorials.net/lesson/behavioral-design-pattern/)
