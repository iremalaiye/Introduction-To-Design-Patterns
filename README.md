**Abstract Class:**  object cannot be created
(new Animal() gives an error),  
other classes can inherit (extends) it, subclasses must override the move() method.  
Acts as a template for all animals.  
*Animal abstract class* 

**Inheritance:** *Cat, Dog extends Animal*  

**Polymorphism:** The same method name may behave differently in different classes.->*animal.move() works differently for both Cat and Dog.* 

**Dynamic Dispatch:** It is the decision at runtime which subclass method will be called while the program is running.->*Animal a = new Dog(); a.move(); → Dog’s move() is called.*

**Composition(has-a relationship):** *The Mover object is located inside Cat and Dog* (has-a).->*Mover mover = new Mover(); mover.move();* 

**Delegation(delegation of authority):** *The moving process is handed over to Mover*   

**Encapsulation**   

**Method Overriding:** Each animal defines its own movement-> *move()*

**Shadowing:** Hides the variable of the same name in the superclass.-> *Location variable in Dog* 

**Single Responsibility Principle (SRP)**  





**method overriding -method overloading**  

override:A subclass redefines a method defined in the superclass with the same name and parameters.  

overload:Defining the same named method in the same class more than once with different parameters.
