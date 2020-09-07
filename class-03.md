# Data Modeling & NoSQL Database

<br><br>

## SQL vs NoSQL Database Differences
* SQL databases are primarily called as Relational Databases (RDBMS); whereas NoSQL database are primarily called as non-relational or distributed database
* SQL databases are table based databases whereas NoSQL databases are document based, key-value pairs, graph databases or wide-column stores. 
* SQL databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data.
* SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable. 
* SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful. In NoSQL database, queries are focused on collection of documents.
* SQL database examples: MySql, Oracle, Sqlite, Postgres and MS-SQL. NoSQL database examples: MongoDB, BigTable, Redis, RavenDb.


<br><br>

## NOSQL DATA MODELING TECHNIQUES:
* NoSQL data modeling often starts from the application-specific queries as opposed to relational modeling:
1. Relational modeling is typically driven by the structure of available data. 
2. NoSQL data modeling is typically driven by application-specific access patterns, i.e. the types of queries to be supported.
* NoSQL data modeling often requires a deeper understanding of data structures and algorithms than relational database modeling does. In this article I describe several well-known data structures that are not specific for NoSQL, but are very useful in practical NoSQL modeling.
<BR><BR>

## Conceptual Techniques
1. Denormalization
2. Aggregates
3.  Application Side Joins
4. Atomic Aggregates
5. Enumerable Keys
6. Dimensionality Reduction
7. Index Table
8. Composite Key Index
9. Aggregation with Composite Keys
10. Inverted Search – Direct Aggregation

<br><br><br><br>

## Review, Research, and Discussion
1. Name 3 advantages to Test Driven Development 
   - TDD reduces the time required for project development.
   - Code flexibility and easier maintenance.
   - Save project costs in the long run.
2. In what case would you need to use beforeEach() or afterEach() in a test suite?
If you have some work you need to do repeatedly for many tests, you can use beforeEach and afterEach.
3. What is one downside of Test Driven Development?
It necessitates a lot of time and effort up front, which can make development feel slow to begin with. Focusing on the simplest design now and not thinking ahead can mean major refactoring requirements. It's difficult to write good tests that cover the essentials and avoid the superfluous.
4. What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
The most important difference between class- and prototype-based inheritance is that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.
5. Name a use case for a static method
Use static when you want to provide class level access to a method.

<br><br><br><br>

## Document the following Vocabulary Terms
* functional programming: is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects.
* pure function : Its return value is the same for the same arguments (no variation with local static variables, non-local variables, mutable reference arguments or input streams from I/O devices).
* higher-order function: function that takes a function as an argument, or returns a function.
* immutable state: (unchangeable object) is an object whose state cannot be modified after it is created. 
* object: one of JavaScript's data types. It is used to store various keyed collections and more complex entities.
* object-oriented programming (OOP): is about creating objects that contain both data and functions.
* class :is an extensible program-code-template for creating objects, providing initial values for state (member variables) and implementations of behavior (member functions or methods).
* prototype : The prototype is an object that is associated with every functions and objects by default in JavaScript, where function's prototype property is accessible and modifiable.
* super :  keyword is used to access and call functions on an object's parent. 
* inheritance :  the mechanism of basing an object or class upon another object (prototype-based inheritance) or class (class-based inheritance), retaining similar implementation.
* constructor : function that creates an instance of a class which is typically called an “object”.
* instance : is an object containing data and behavior described by the class.
* context : It refers to the object within the function being executed.
* this:  this keyword refers to an object, that object which is executing the current bit of javascript code.
* Test Driven Development (TDD) : is a process for writing software that provably satisfies the software requirements.
* Jest : JavaScript testing framework maintained by Facebook, Inc. with a focus on simplicity.
* Continuous Integration (CI) :evelopment practice that requires developers to integrate code into a shared repository several times a day. 
* unit test : level of software testing where individual units/ components of a software are tested.







