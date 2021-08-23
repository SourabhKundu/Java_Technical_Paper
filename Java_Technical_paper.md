# Java 
**Java** is a general-purpose, class-based, object-oriented programming language designed for having lesser implementation dependencies. It is a computing platform for application development. Java is fast, secure, and reliable, therefore. It is widely used for developing Java applications in laptops, data centers, game consoles, scientific supercomputers, cell phones, etc.

## What is Java Platform?
Java Platform is a collection of programs that help programmers to develop and run Java programming applications efficiently. It includes an execution engine, a compiler, and a set of libraries in it. It is a set of computer software and specifications. 

## Where Java is used?
There are many devices where java is currently used. Some of them are as follows:
1. Desktop Applications
2. Web Applications
3. Mobile
4. Embedded System
4. Robotics
5. Games etc.


Now lets see code of hello world program.
```
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

## Get Started
### Java Install
Some PCs might have Java already installed, to check it in windows command prompt 
> C:\Users\Your Name>java -version

If Java is not there we have to download it manually by going to Java offical website.

## Java Variables
Variables are containers for storing data values.
In Java, there are different types of variables, for example:
* String
* Int
* float
* char
* boolean

### Declaring(Creating) Variables
*type variable = value ;*

Example:
```
string name= "John";
int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";
 ```

 ### Data Types
 Data types in Java are divided into two groups:
 * Primitive data types - includes byte, short, int, long, double, float, boolean, char.
 * Non-primitive data types - such as String, Arrays and Classes.

 ## Java Type Casting
 Type casting is when you assign a value of one primitive data type to another type.
 In Java there are two types of casting:
 * Widening Casting(automatically)
 * Narrowing Casting(manually)

 ### Widening Casting
 It is done automatically when passing a smaller size type to a larger size type:
 ```
 public class Main {
  public static void main(String[] args) {
    int myInt = 9;
    double myDouble = myInt; // Automatic casting: int to double

    System.out.println(myInt);      // Outputs 9
    System.out.println(myDouble);   // Outputs 9.0
  }
}
 ```

 ### Narrowing Casting
 Narrowing casting must be done manually by placing the type in parentheses in front of the value:
 ```
 public class Main {
  public static void main(String[] args) {
    double myDouble = 9.78d;
    int myInt = (int) myDouble; // Manual casting: double to int

    System.out.println(myDouble);   // Outputs 9.78
    System.out.println(myInt);      // Outputs 9
  }
}
 ```

 ## Java Operators
 operators are used to perform operations on variables and values.
 Types of operators in Java:
 * Arithmetic Operators(+,-,*,/)
 * Assignment Operators(=,==)
 * Comparison operators(<,>)
 * Logical operators(!,&)
 * Bitwise operators

 ## Java Strings
 Strings are used for storing text. A **String** variable contains a collection of characters surrounded by double quotes:
 > String greeting = "Hello";

 ## Java OOP
 ### Java - What is OOP?
 OOP stands for **Object-Oriented Programming.**

Procedural programming is about writing procedures or methods that perform operations on the data, while object-oriented programming is about creating objects that contain both data and methods.

Object-oriented programming has several advantages over procedural programming:
* OOP is faster and easier to execute
* OOP provides a clear structure for the programs
* OOP helps to keep the Java code DRY "Don't Repeat Yourself", and makes the code easier to maintain, modify and debug.

### Java - What are Classes and Objects?
Classes and objects are the two main aspects of object-oriented programming.
To see difference between classes and objects look at the example:

**class** - Fruit
**objects** - Apple, Banana, Mango

### Java Classes/Objects
Everything in Java is associated with classes and objects, along with its attributes and methods.

**Create a Class**
```
public class Main {
  int x = 5;
}
```

**Create an Object**
```
public class Main {
  int x = 5;

  public static void main(String[] args) {
    Main myObj = new Main();
    System.out.println(myObj.x);
  }
}
```
### **Java Encapsulation** 
The meaning of **Encapsulation**, is to make sure that "sensitive" data is hidden from users. To achieve this, you must:
* declare class variables/attributes as private
* provide public get and set methods to access and update the value of a private variable

### **Java Inheritance**
In Java, it is possible to inherit attributes and methods from one class to another. We group the "inheritance concept" into two categories:
* **subclass**(child) - the class that inherits from another class
* **superclass**(parent) - the class being inherited from

> To inherit from a class, use the extends keyword.

### **Java Polymorphism**
Polymorphism means "many forms", and it occurs when we have many classes that are related to each other by inheritance.

Like we specified in the previous chapter; Inheritance lets us inherit attributes and methods from another class. Polymorphism uses those methods to perform different tasks. This allows us to perform a single action in different ways.

For example, think of a superclass called Animal that has a method called animalSound(). Subclasses of Animals could be Pigs, Cats, Dogs, Birds - And they also have their own implementation of an animal sound (the pig oinks, and the cat meows, etc.):

### **Java Abstraction** 
Data abstraction is the process of hiding certain details and showing only essential information to the user.
Abstraction can be achieved with either abstract classes or interfaces 
> The abstract keyword is a non-access modifier, used for classes and methods
```
abstract class Animal {
  public abstract void animalSound();
  public void sleep() {
    System.out.println("Zzz");
  }
}
```

There are many for topics to cover in Java this technical paper was just a brief introduction to Java.

## References
> https://www.w3schools.com/java/java_abstract.asp
> http://www.corejavaguru.com/java/basic/overview
> https://guides.github.com/features/mastering-markdown/




