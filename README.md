# Lab 02 -- Chapter 01

## Define the following terms:
* object: A specific instance of a class (can be a combination of variables, functions, and data structures)  
* class: A blueprint or set of instructions from which individual objects are created
* instance: A specific realization of any object that emphasizes the distinct identity of the object.
* method: A collection of statements in a class used to manipulate (mutators) or access (accessors) information from an object. (Behaves like a function in mathematics) 
* signature (or heading): Name of the method and the type of parameter. I.e. the following signature changes the size of the instance `box` of class `Box` and does not give an output.
* ```
* void changeSize(Box box)
* ```
* parameter: An input of the moethod. I.e. `box` is the parameter in the example above. 
* type: Define what values the parameter is allowed to be.
* state: Set of values desribing an object
* source code: Collection of written commands that compiles to create an executable program.
* return value: Output of a method
* compiler: Transforms source code into computer language (forces the computer to read the instructions).
## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?

* 0 :: int, double, float? 
* "hello" :: String   
* 101 :: int, double, float?
* -1 :: int, double, float?
* true :: boolean
* "33" :: String 
* 3.1415 = double, float?

## What would you have to do to add a new field, for example one called name, to a circle object?
```
private String name;
```
## Write the header for a method named send that has one parameter of type String, and does not return a value.
```
public void send (String var1)
```
## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
```
public int average ( int v1, int v2)
```

## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
The book is an object of class Books.
Or the book is a class called BluJBook and the objects are different copies of the book.

## Can an object have several different classes? Discuss.
An object cannot have several different classes. This is because an object is an entity that is essentially created from a class. It would not make any sense for an object to have or essentially create classes if the classes are what has created it in the first place. That being said, the object would still be able to implement multiple interfaces, and it can still subclass a class with multiple superclasses, but it cannot be more than one object at a time.
