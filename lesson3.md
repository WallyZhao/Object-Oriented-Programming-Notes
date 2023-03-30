# Notes for Lesson 3

## Inheritance
### What is inheritance?
* When an object or class is based on another class. (It's features come from a parent class)

### Uses of Inheritance 

- When a child inherits from a parent class, it doesn't need a intialization method. 
#### UNLESS it requires new attributes (Example of a child using ```__init__``` because it has new attributes) 
![example of single inheritance](https://cdn.discordapp.com/attachments/483839712495140865/1090798686730199131/image.png "Example of single Inheritance") 

## Rule of thumb for Inheritance
#### "If you modify one, you must modify the other one."

## super() method  
* Method that allows classes to call back to the Parent class 
  * Prevents you from doing ```ParentClass.method(self)``` as it can get confusing 
#### Same code above, but using super() instead of ```ParentClass.method(self)```
![example of single inheritance using super()](https://cdn.discordapp.com/attachments/483839712495140865/1090802312236236800/image.png "Example using super()")
### Types of Inheritances
* Single Inheritance: A subclass inheriting the features from a parent class 
* Multiple Inheritance: A subclass inheriting the features from multiple different parent classes 
* Mutlilevel Inheritance: A subclass that inherits from another subclass A --> B --> C --> ... 

![visualization of inheritance](https://www.edureka.co/blog/wp-content/uploads/2017/07/Types-of-Inheritance.jpg)

## How this ties in with Polymorphism:

* Inheritance can inherit features from a parent class, other words methods that can be used in different classes.
  * the idea to take away is that Different classes (non-inherited) can have the same named methods.
  * Within in a set of inherited classes have the same methods. 
