## Design Pattern

* A Repository mediates between the domain and data mapping layers, acting like an in-memory domain object collection. Client objects construct query specifications declaratively and submit them to Repository for satisfaction. Objects can be added to and removed from the Repository, as they can from a simple collection of objects, and the mapping code encapsulated by the Repository will carry out the appropriate operations behind the scenes.
* Repository pattern separates the data access logic and maps it to the business entities in the business logic. Communication between the data access logic and the business logic  is done through interfaces.
* In order to separate our Controllers from the database in right manner, we are going to abstract that interaction into repositories. A repository is simply an interface between two things.
* Repositories allow you to create a flexible abstraction layer between your database and your Controller. Doing this enables you to separate those concerns and it prevents your Controllers being too tightly coupled with your Database.

<br><br>

## Testing Node.js + Mongoose with an in-memory database
* allows us to start a mongod process that stores the data in memory
* pros:
  1. No need for mocks
  2. Faster development
  3. More reliable tests.
  4. Tests are easier to build

* Cons:
  1. The in-memory database probably needs seeding
  2. More memory usage
  3. Tests take longer to run (depending on your hardware).
  
  <br><br><br>

## Review, Research, and Discussion  
1. Why would a developer choose to make data models?
A data model helps design the database at the conceptual, physical and logical levels. Data Model structure helps to define the relational tables, primary and foreign keys and stored procedures. It provides a clear picture of the base data and can be used by database developers to create a physical database.
2. What purpose do CRUD operations serve?
A customer may use CRUD to create an account and access that account when returning to a particular site. The user may then update personal data or change billing information.
3. What kind of database is Postgres? What kind of database is MongoDB?
postgres is SQL & MongoDB is NOSQL.
4. What is Mongoose and why do we need it?
Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. ... It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.

<br><br><br><br>

## Document the following Vocabulary Terms
* database:  is an organized collection of data, generally stored and accessed electronically from a computer system
* data model:  define how the logical structure of a database is modeled
* CRUD: create, read, update, and delete are the four basic functions of persistent storage
* schema: is a collection of logical structures of data.
* sanitize : the process of deliberately, permanently and irreversibly removing or destroying the data stored on a memory device to make it unrecoverable⁠
* SQL : language for storing, manipulating and retrieving data stored in a relational database. 
* NOSQL : are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph.
* MongoDB: cross-platform document-oriented database program. Classified as a NoSQL database program
* Mongoose: Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment.
* Record:  fields and contains all the data about one particular item in a database.


