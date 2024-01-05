# Creational Design Pattern

It plays an important role in how we create objects. Provides a way to encapsulate the instantiation process of objects, making the system more flexible and less dependent on the specifics of classes.

Traditionally object-oriented programming, instantiation involves using constructors directly within the client code which leads to tight coupling between the class implementation and the client.

Creational patterns solve this problem by abstracting the process of instance creation so that the system can remain independent of how its objects are defined, created, and represented.

## Benefits of Creational Design Patterns

- **Code maintainability**: Reduces dependencies between objects and makes the system more abstract, thus making the code easier to manage and extend.
- **Encapsulation of Object Creation**: The client does not need to know the classes initializing new objects, which promotes loose coupling.
- **Flexibility**: Allows switching between different implementations without modifying the client code. This isolates the code that constructs objects from the code that uses them, leading to lower coupling and increased flexibility.
- **Scalability**: The system becomes more scalable as new object types can be introduced with minimal changes to the existing code.

## When to use it?

Creational Design Patterns are essential when the system needs to be independent of how its objects are created, composed, and represented. They are useful in the following scenarios:

- **When the system configuration needs to create various objects**: These patterns can dynamically decide the class of that object that needs to be created based on the configuration or environment.
- **When families of related objects are designed to be used together**: Ensuring that objects that need to work together can be created using a particular design pattern.
- **When you want to hide the implementation of an object pool**: Managing the initialization and recycling of objects that are expensive to create (like connections to a database).
- **Resource Management**: Applications need to efficiently manage expensive or complex resources, ensuring that instances are created only when necessary and according to the current context.

## Types of creational design pattern

- **Singleton**: Learn how to ensure a class has only one instance. This pattern is useful for situations where exactly one instance is needed to coordinate actions across the system, such as a connection pool or configuration settings.

- **Factory Method**: Create objects without specifying the exact class of the object. This pattern is useful when a class cannot anticipate the class of objects it must create or when subclasses want to specify the objects it creates.

- **Abstract Factory**: Provide an interface for creating families of related or dependent objects. This pattern uses factory methods to do the instantiation and can deliver families of related objects.

- **Prototype**: Clone objects to avoid expensive creation processes. This pattern is useful when creating objects directly from a prototype is more efficient than performing an instantiation following a standard method.

- **Builder**: Build complex objects step by step. This pattern is used for creating complex objects that require a lot of steps to construct or need many optional and mandatory parts.

## References

- [Refactor Guru](https://refactoring.guru/design-patterns/classification)
- [Dot Net Tutorials](https://dotnettutorials.net/course/dot-net-design-patterns/)
