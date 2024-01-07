# Structural Design Pattern

A structural design pattern is a type of software design pattern that focuses on organizing and composing objects and classes to form larger, more flexible structures while keeping theme efficient and easy to maintain. These patterns help define relationships between entities, ensuring that the system remains scalable and adaptable.

The structural design patterns simplify the design by identifying a simple way to manage the relationships between entities. They allow developers to obtain new functionalities by composing objects and classes. They focus on how classes inherit from each other and how they are composed from other classes.

## Benefits of Structural Design Patterns

- **Composition Over Inheritance**: They emphasize object composition rather than deep inheritance hierarchies.

- **Efficient Relationships**: They help create efficient relationships between objects, reducing dependencies and coupling.

- **Flexibility & Maintainability**: They allow easy modifications without altering existing code significantly.

## When to use it?

Structural design patterns are useful when you need to create flexible, scalable, and maintainable software architectures. Here are some specific scenarios where these patterns shine:

1. **When integrating incompatible interface**: If you need to connect two systems or components with different interfaces, structural pattern (`Adapter pattern`) can bridge the gap without modifying the existing code.
2. **When simplifying interactions with complex subsystems**: If your system consists of multiple interdependent components, using a structural pattern (`Facade pattern`) can provide a unified, simplified interface to improve usability.
3. **When working with hierarchical or tree-like structures**: When dealing with UI components, file systems, or document structures, structural pattern (`Composite pattern`) allows treating individual and composite objects uniformly.
4. **When you need to dynamically add or modify behavior**: Instead of modifying an existing class, structural structural pattern (`Decorator pattern`) enables adding new functionality at runtime without altering the original code.
5. **When optimizing resource usage**: If your application needs to handle a large number of similar objects efficiently, structural pattern (`Flyweight pattern`) can minimize memory consumption by sharing common data.
6. **When controlling access to an object**: The structural pattern (`Proxy pattern`) is useful for adding security, lazy initialization, logging, or caching without exposing direct access to the underlying object.

## Types of structural design pattern

1. **Adapter Pattern**: Allows objects with incompatible interfaces to collaborate. It's commonly used when existing classes ned to be used and modifying their interfaces isn't an option, such as when dealing with third-party or legacy systems.
2. **Facade Pattern**: Provides a simplified interface to aa complex subsystem. It is used to provide a cleaner API over a set of interfaces in a subsystem.
3. **Decorator Pattern**: Adds new functionalities to objects dynamically by placing these objects inside special wrapper objects that contain the behaviors. This is useful when we want to add features to objects without sub-classing.
4. **Composite Pattern**: Allows us to compose objects into tree structures to represent part-whole hierarchies. It lets clients treat individual objects and compositions uniformly, ideal for graphical applications or file system where objects might contain other objects.
5. **Proxy Pattern**: Provides a surrogate or placeholder for another object to control access to it. This is useful when a program requires a large number of objects with similar states.
6. **Flyweight Pattern**: Minimizes memory use by sharing as much data as possible with similar objects. It is useful when a program requires a large number of objects with similar states.
7. **Bridge Pattern**: Separates an abstraction from its implementation os that the two can vary independently. This is useful both the interface and underlying implementations can have multiple variants and should be interchangeable.

## References

- [Refactor Guru](https://refactoring.guru/design-patterns/structural-patterns)
- [Dot Net Tutorials](https://dotnettutorials.net/lesson/structural-design-pattern/)
