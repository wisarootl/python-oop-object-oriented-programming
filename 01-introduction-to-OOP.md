# Introduction to OOP and Key Concepts

- OOP : programming paradigm that organizes software deign around objects

- Programming Paradigm :

  - an approach used to solve problems with code
  - a style or way of programming
  - many Programming Paradigm e.g., imperative, functional, declarative, logic

- Class : blueprint of object, have state and behavior

- Object : instance of a class, have state and behavior

- One program can have multiple paradigm

- Advantages of OOP

  - Modularity : separate and independence but we can combine to improve functionality
  - Reusability : object is reusable. faster and lower cost for development
  - Extensibility : object can be extended for new attributes and behavior
  - Easier to maintain
  - High quality of software

- Terminology
  - Pythonic : adjective commonly used to describe an approach to programming that follows the standards, rules, and best practice of the Python programming language.
  - Instance : a concrete object that is created from the class “blueprint”.
  - Method : an “action” defined in the class that the instances of the class can perform. (similar to function)
  - Mutation : the result of changing the original object in memory instead of making a separate copy of the object.
  - Aliasing : when two or more names (variables) point to the same memory address
  - Cloning : process of creating a separate (deep) copy of an object.

# OOP Design

📌 An important tip is that before we start writing a program using Object-Oriented Programming, we need to analyze what objects will be needed, their attributes, methods, and interactions.

An example of this would be the Tic-Tac-Toe project that we just created. Based on the description of the game, we knew that we needed to define a `Player` class and a `Board` class and after careful analysis, we decided to include a `Move` class.

But how can we analyze the problem description?

This is the goal of Object-Oriented Analysis and Design.

Its four main goals are to...

- Identify Classes.

- Identify Attributes.

- Identify Methods.

- Identify relationships and interactions between the objects of the classes.

🔹 Guidelines

- We can identify potential classes from the nouns in a problem description.

- We can identify potential attributes from the adjectives (and nouns) in a problem description.

- We can identify potential methods from the verbs that describe actions that the objects can take in the program.

After this initial analysis where we write all possible classes, attributes, and methods that we might need to include, we perform a deeper analysis to determine which ones will be relevant for our program and how the objects will interact with each other. This is how we create the final structure of our program.
