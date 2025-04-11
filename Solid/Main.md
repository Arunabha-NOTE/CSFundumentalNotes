# SOLID Principles

1. **S -> Single Responsibility Principle**  
   Every class should have one and only one reason to change.  
   *Example*: A class handling user authentication should not also handle logging.

2. **O -> Open/Closed Principle**  
   Open for extension but closed for modification.  
   *Example*: Adding new functionality should be achieved by extending existing code, not modifying it.

3. **L -> Liskov Substitution Principle**  
   Objects of a superclass should be replaceable by objects of a subclass without altering the correctness of your program.  
   *Example*: If a function works with a parent class, it should also work with any subclass without issues.

4. **I -> Interface Segregation Principle**  
   Clients should not be forced to implement interfaces they do not use.  
   *Example*: Split large interfaces into smaller, more specific ones to ensure classes only implement what they need.

5. **D -> Dependency Inversion Principle**  
   High-level modules should not depend on low-level modules. Both should depend on abstractions.  
   *Example*: Use interfaces or abstract classes to decouple dependencies.

([Source](https://www.youtube.com/watch?v=V3TUEeB0kW0))