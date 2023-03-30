# Iterable Objects (Won't be on test) 
## Definition
* Objects that you can iterate through like a sequence
  * Ex: Strings and Lists 

```
def __iter__(self)
  return self
```
## Different methods 
```
__iter__
```
* Allows our object to be iterable, when called upon. (returns itself)

```
__next__()
```
* Allows us to get the next value when iterating
 
 # Summary of OOP 
 
 ### Class: Description of a new object that can be made 
  * Attributes: Variables/Data that belongs to the class
  * Methods: Functions that you call upon to use 

### Encapsulation: Information hiding, restricting the access to the classes/objects' attributes 

#### Setter and Getter methods 
* *Setter* --> A method that allows you to "set" or mutate an attribute in the class
* *Getter* --> A method that allows you to access an attribute in a given class 

### Inheritance: When an object or a class is based on another class that is already created
  * Single - A child class inheriting from a parent class
  * Multiple - A child class inheriting from multiple parent classes 
  * Multilevel - Also known as multi-generational (subclass inheriting from another subclass) 

### Polymorphism: A method that can be used across different classes that is dependent on the parameters 

*Poly* --> Many 

*Morphism* --> Forms 

You can have:

  * Two different classes have the same attributes and methods 
  * A child of a parent can have an **overrided** method where the child would use the method differently.\
   

