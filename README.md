# Factory Method Design Pattern

Factory method is one of the more popularly used design patterns (and in some ways the opposite of the Singleton pattern)

Concepts:
- Doesn't expose instantiation logic (the client knows nothing about the type of object being created)
- Defers instantiation to the subclasses (the parameters are used to determine the concrete type)
- The method to request an object is typically parameterized
- Objects returned by a factory method are often referred to as products.
- The client knows about common interfaces that the factory exposes
- Specified by architecture, implemented by user
Exampes:
-Calendar
-ResourceBundle
-NumberFormat

Factory is responsible for creating instances and managing the lifecycle.
The Factory Method pattern suggests that you replace creating new objects (using the new operator) with calls to a special factory method.
The objects are still created via the new operator, but it’s being called from within the factory method.
