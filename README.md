# Data_Structures_and_Algorithms in Java :

Object - An object in Java is an actual instance of a class. While a class is just a blueprint, an object is the real thing created from it. For example, if Car is a class, then myCar is an object of that class. The object can store specific values (like color = "Red") and perform actions defined in the class (like drive). Objects allow us to use and manipulate real data based on the class structure.

Class - A class in Java is a blueprint for creating objects. It defines properties (variables) and behaviors (methods) that the objects will have. For example, a Car class might have a color and a method to drive. You use the class to create real-world objects (like a red car), and then interact with them using the class's defined structure. Classes help organize and reuse code in object-oriented programming.

Inheritance - Inheritance in Java is a feature that lets one class (called the child or subclass) use the properties and methods of another class (called the parent or superclass). It helps in reusing code and creating a relationship between classes. For example, if a class Animal has a method eat(), a class `Dog` can inherit from it and use eat() without writing it again. This makes programs easier to manage and extend.

Encapsulation - Encapsulation in Java means wrapping data (variables) and code (methods) together into a single unit — a class — and protecting that data from outside access. It is done by making variables private and providing public getter and setter methods to access or update them. For example, a BankAccount class can hide its balance and allow access only through methods like deposit() and getBalance(). This keeps the data safe and secure from unwanted changes.

Polymorphism - Polymorphism in Java means one thing behaving in different ways. It allows objects to respond differently to the same method call. There are two types: compile-time polymorphism(method overloading) and runtime polymorphism (method overriding). For example, a print() method might print text, numbers, or images depending on the input. Polymorphism makes code more flexible and easier to extend or modify.

Abstraction - Abstraction in Java means hiding unnecessary details and showing only the important parts of an object. It helps you focus on what an object does instead of how it does it. This is done using abstract classes or interfaces. For example, when you drive a car, you just use the steering and pedals—you don’t need to know how the engine works inside. Similarly, abstraction lets programmers use complex systems easily without dealing with all the inner code.

These are the 5 main concepts of OOPS :

1. Object –  A real-world entity
2. Class – Blueprint of collection of things 
3. Inheritance  – Reusing code from parent class
4. Encapsulation – Data protection and control
5. Polymorphism – One thing, many forms
6. Abstraction – Hiding complex details

OOPS means Object Oriented Programming system


Variable – A variable in Java is like a container that stores data. It has a name a type, and a value. For example, int age = 22; creates a variable named `age` that stores the number 22. Java is a statically-typed language, so you must declare the type (like int, String, or boolean) before using the variable. Variables help store and use data in a program as it runs.

Method – A method in Java is a block of code that performs a specific task. It's like a function — you define it once and can use it many times. Methods help organize code, make it reusable, and improve readability. For example, a method add(int a, int b) can take two numbers and return their sum. You call methods using objects or class names, depending on whether they're instance or static methods.

Array – An array in Java is a container that holds a fixed number of values of the same data type. For example, you can create an array of integers like int[] numbers = {1, 2, 3, 4};. Each element in the array is accessed using an index, starting from 0. Arrays are useful for storing and working with multiple values together, but their size is fixed once created.

String –  A String in Java is a sequence of characters used to store and work with text. For example, "Hello" is a String. Java treats String as a class, not a primitive type, and it offers many built-in methods like length(), toUpperCase(), and substring() to manipulate text easily. Strings are immutable, which means once created, their value cannot be changed — any changes create a new String.

File Handling in Java –

File handling allows Java programs to create, read, write, update, and delete files stored on the computer.


 Main Purposes-

* Store data permanently (outside of RAM)
* Save program output to a file
* Read input from external files


 Common Classes-

 Class               Purpose                                   
| ---------------- | ----------------------------------------- |
| `File`           | For creating, checking, or deleting files |
| `FileWriter`     | For writing data to a file                |
| `FileReader`     | For reading data from a file              |
| `Scanner`        | For reading files line-by-line easily     |
| `BufferedReader` | For reading large files efficiently       |


 Common Operations-

  Create a file
  Write to a file
  Append data
  Read data
  Delete a file

 Exceptions to Handle -

`IOException` → When reading/writing fails
`FileNotFoundException` → When file does not exist

 Use Cases-

 Saving user data or logs
 Loading configuration or input
 Storing output of a program

