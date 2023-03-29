# Notes for Lesson 2
## Base Function definitions


## Encapsulation
### What is encapsulation?
* Information hiding, encryption. Restricting access to classes/objects' attributes and methods. 
  * In Python you use a special system to hide attributes and methods by using double underscores ```__``` as a prefix
  
```python
class Student:
  def __init__(self,nameF, nameL, num):
    self.firstName = nameF
    self.lastName = nameL
    self.__studentNumber = num
  
  def __getStudentNumber(self):
    return self.__studentNumber
```
## Overrides 
### Overloading and Overriding 

* Overloading: Two methods in **one class** that have the same method name, but different parameters (variables) 
#### Important note: Overloading does not exist in Python 3 
* Overriding: Two methods with the same method name and parameters
#### Uses of overriding
  * Overriding allows the child class to provide specific implementation for a method that exists in the parent class
  * You can also override built-in **magic-methods** (Start and end in ```__```) OR base functions  

## Polymorphism 
### What is Polymorphism?
* A method that can be used across different classes and object that is depend on the parameters. 

_Poly_ --> Many

_Morphism_ --> Forms 
### Examples that utilize Polymorphism and Override are:
* Two different classes having the same attributes and methods.
* A child of aprent that has an overried method where the child would use the method differently. 

#### Example of two different classes with same attributes and methods
```python
class Bear:
    def sound(self):
        print("Groarrr")
 
class Dog:
    def sound(self):
        print("Woof woof!")

# Creating the method to call back to both class methods 
def makeSound(animalType):
    animalType.sound()

# Assigning the two classes to a parameter
bearObj = Bear()    
dogObj = Dog()


makeSound(bearObj)
makeSound(dogObj)
```
## Benefits of Override









