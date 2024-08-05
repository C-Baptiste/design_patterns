# Gang of Four Design Patterns
## Creational Design Patterns

- Abstract Factory. Allows the creation of objects without specifying their concrete type.
- Builder. Uses to create complex objects.
- Factory Method. Creates objects without specifying the exact class to create.
- Prototype. Creates a new object from an existing object.
- Singleton. Ensures only one instance of an object is created.

## Structural Design Patterns

- Adapter. Allows for two incompatible classes to work together by wrapping an interface around one of the existing classes.
- Bridge. Decouples an abstraction so two classes can vary independently.
- Composite. Takes a group of objects into a single object.
- Decorator. Allows for an object’s behavior to be extended dynamically at run time.
- Facade. Provides a simple interface to a more complex underlying object.
- Flyweight. Reduces the cost of complex object models.
- Proxy. Provides a placeholder interface to an underlying object to control access, reduce cost, or reduce complexity.

## Behavior Design Patterns

- Chain of Responsibility. Delegates commands to a chain of processing objects.
- Command. Creates objects which encapsulate actions and parameters.
- Interpreter. Implements a specialized language.
- Iterator. Accesses the elements of an object sequentially without exposing its underlying representation.
- Mediator. Allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
- Memento. Provides the ability to restore an object to its previous state.
- Observer. Is a publish/subscribe pattern which allows a number of observer objects to see an event.
- State. Allows an object to alter its behavior when its internal state changes.
- Strategy. Allows one of a family of algorithms to be selected on-the-fly at run-time.
- Template Method. Defines the skeleton of an algorithm as an abstract class, allowing its sub-classes to provide concrete behavior.
- Visitor. Separates an algorithm from an object structure by moving the hierarchy of methods into one object.


## Creational Patterns
- Abstract Factory (87) Provide an interface for creating families of related or dependent
objects without specifying their concrete classes.
- Builder (97) Separate the construction of a complex object from its representation so
that the same construction process can create different representations.
- Factory Method (107) Define an interface for creating an object, but let subclasses de-
cide which class to instantiate. Factory Method lets a class defer instantiation to
subclasses.
- Prototype (117) Specify the kinds of objects to create using a prototypical instance, and
create new objects by copying this prototype.
- Singleton (127) Ensure a class only has one instance, and provide a global point of
access to it.
## Structural Patterns
- Adapter (139) Convert the interface of a class into another interface clients expect.
Adapter lets classes work together that couldn't otherwise because of incompat-
ible interfaces.
- Bridge (151) Decouple an abstraction from its implementation so that the two can vary
independently.
- Composite (163) Compose objects into tree structures to represent part-whole hierar-
chies. Composite lets clients treat individual objects and compositions of objects
uniformly.
- Decorator (175) Attach additional responsibilities to an object dynamically. Decorators
provide a flexible alternative to subclassing for extending functionality.
- Facade (185) Provide a unified interface to a set of interfaces in a subsystem. Facade
defines a higher-level interface that makes the subsystem easier to use.
- Flyweight (195) Use sharing to support large numbers of fine-grained objects effi-
ciently.
- Proxy (207) Provide a surrogate or placeholder for another object to control access to
it.
## Behavioral Patterns
- Chain of Responsibility (223) Avoid coupling the sender of a request to its receiver by
giving more than one object a chance to handle the request. Chain the receiving
objects and pass the request along the chain until an object handles it.
- Command (233) Encapsulate a request as an object, thereby letting you parameter-
ize clients with different requests, queue or log requests, and support undoable
operations.
- Interpreter (243) Given a language, define a represention for its grammar along with
an interpreter that uses the representation to interpret sentences in the language.
- Iterator (257) Provide a way to access the elements of an aggregate object sequentially
without exposing its underlying representation.
- Mediator (273) Define an object that encapsulates how a set of objects interact. Me-
diator promotes loose coupling by keeping objects from referring to each other
explicitly, and it lets you vary their interaction independently.
- Memento (283) Without violating encapsulation, capture and externalize an object's
internal state so that the object can be restored to this state later.
- Observer (293) Define a one-to-many dependency between objects so that when one
object changes state, all its dependents are notified and updated automatically.
- State (305) Allow an object to alter its behavior when its internal state changes. The
object will appear to change its class.
- Strategy (315) Define a family of algorithms, encapsulate each one, and make them
interchangeable. Strategy lets the algorithm vary independently from clients that
use it.
- Template Method (325) Define the skeleton of an algorithm in an operation, deferring
some steps to subclasses. Template Method lets subclasses redefine certain steps
of an algorithm without changing the algorithm's structure.
- Visitor (331) Represent an operation to be performed on the elements of an object
structure. Visitor lets you define a new operation without changing the classes of
the elements on which it operat