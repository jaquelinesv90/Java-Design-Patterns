Design patterns are typical solutions to common problems, in software design.Each pattern is like a blueprint
that you can customize to solve a particular design problem in your code.

They represent the best practices used by experienced object-oriented software developers.


SOLID principles of Object-Oriented Design.
 Design principles encourage us to create more maintainable, understandable, and flexible software.
 Consequently, as our applications grow in size,we can reduce their complexity and save ourselves a lot
 of headaches further down the road.

1. SRP - Single Responsibility 
2. OCP - Open/Closed 
3. LSP - Liskov Substitution 
4. ISP - Interface Segregation 
5. DIP - Dependency Inversion 


1.SRP - Single Responsibility
 * Each responsibility should be a separate class,because each responsibility is an axis of change.
 * A class should have one, and only one,reason to change.
 * If a change to the business rules causes a class to change, then a change to the database schema,
GUI, report format, or any other segment of the system should not force that class to change.

2. OCP - Open/Closed
 * A class should be open for extension, but closed for modification(you should never need to change
existing code or classes,all new functionality can be added by adding new subclasses or methods, or by 
reusing )
 
