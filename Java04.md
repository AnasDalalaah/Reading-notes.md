# OOP

## Objects

- A typical Java program creates many objects, which as you know, interact by invoking methods.
- Through these object interactions, a program can carry out various tasks, such as implementing a GUI, running an animation, or sending and receiving information over a network.
- Once an object has completed the work for which it was created, its resources are recycled for use by other objects.

### Creating Objects

- As you know, a class provides the blueprint for objects; you create an object from a class.

**Declaration**: The code set in bold are all variable declarations that associate a variable name with an object type.
**Instantiation**: The `new` keyword is a Java operator that creates the object.
**Initialization**: The `new` operator is followed by a call to a constructor, which initializes the new object.

### Difference between object and class 

The difference between a class and an object is that a class is a logical entity and an object is a physical thing. In Java, the "class" keyword may be used to create a class, whereas the "new" keyword can be used to create an object. A class, on the other hand, does not allocate memory space; on the other hand, an object does.

### Provide Constructor to Class

The constructor of the class may be used to build objects from the class blueprint. I may give information to a constructor or method as arguments, but I must define the type of data I'm giving. The varargs technique allows the user to supply an arbitrary value to a method.

1. Modifiers such as public, private, and a number of others that you will encounter later.
2. The class name, with the initial letter **_capitalized_** by convention.
3. The name of the class's parent (superclass), if any, preceded by the keyword extends. A class can only extend (subclass) one parent.
4. A comma-separated list of interfaces implemented by the class, if any, preceded by the keyword implements. A class can implement more than one interface.
5. The class body, surrounded by braces, {}.

### Overloading Methods

- The Java programming language supports overloading methods, and Java can distinguish between methods with different method signatures
- This means that methods within a class can have the same name if they have different parameter lists.

# test 
### Providing Constructors for Your Classes

- A class contains constructors that are invoked to create objects from the class blueprint. Constructor declarations look like method declarations—except that they use the name of the class and have no return type.
### Returning a Class or Interface

- If this section confuses you, skip it and return to it after you have finished the lesson on interfaces and inheritance.

- When a method uses a class name as its return type, such as whosFastest does, the class of the type of the returned object must be either a subclass of, or the exact class of, the return type.
### Binary, Decimal and Hexadecimal Numbers

There is a decimal point in decimals that helps us understand the location of a number. The decimal number system is known as Base 10 since it is based on the number 10. And the digits 0 to 9 are “symbols.”
