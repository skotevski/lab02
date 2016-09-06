# Lab 02 -- Chapter 01

## Define the following terms:
* object, A specific instance of a class (can be a combination of variables, functions, and data structures)  
* class, A blueprint or set of instructions from which individual objects are created
* instance, A specific realization of any object that emphasizes the distinct identity of the object.
* method, A certain procedure that is associated with an object. 
* signature, Code that includes the method name, and the number, types and order of its parameters, and is the smallest type of a method. 
* parameter, A special kind of variable in that is used to pass information between functions or procedures. 
* type, A classification identifying one of various types of data that determines the possible values for that type, the operations that can be done on values of that type, the meaning of the data, and the way values of that type can be stored.
* state, All of the stored information, at a given instant in time, that the circuit or program has access to.
* source code, The only stage where a programmer would be able to read and modify a certain computer program.
* return value, Whatever the function is returning (Examples include the value of a variable, an object, a reference, or anything else
* compiler, A program or set of programs that transforms source code written in a programming language (the source language) into another computer language (the target language), with the latter often having a binary form known as object code. Compilers also effectively transform the source code into a code that the computer can read and utilize. 

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)

## What are the types of the following values?

* 0 = Byte 
* "hello" = string   
* 101 = Short
* -1 = byte
* true = boolean
* "33" = byte 
* 3.1415 = float 

## What would you have to do to add a new field, for example one called name, to a circle object?
In order to add a new field, in this case "name", to a circular object, you would have to make sure that the circle object is first assigned to a class. After that, you would write 

public static void main (String[] args) {
Circleobject = new circleobject ();
}

(Honestly I was very confused with this question, so after researching for a while, this was the best thing I've found, and I am pretty sure it is still incorrect)


## Write the header for a method named send that has one parameter of type String, and does not return a value.
public static String send(String a) {
  // body
}
## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
 public static int average (int a, int b) {
   return a or b;
  }
## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
The book that I am reading right now is a class. Some of the objects that would be in the class book, would be the amount of pages the book has, the color of the cover of the book, the author(s) of the book, the publication date, the chapters of the book, the contents inside the chapters etc. 

## Can an object have several different classes? Discuss.
An object cannot have several different classes. This is because an object is an entity that is essentially created from a class. It would not make any sense for an object to have or essentially create classes if the classes are what has created it in the first place. That being said, the object would still be able to implement multiple interfaces, and it can still subclass a class with multiple superclasses, but it cannot be more than one object at a time.
