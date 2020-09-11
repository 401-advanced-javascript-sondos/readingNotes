## http basics
* HTTP stands for Hypertext Transfer Protocol. It's a stateless, application-layer protocol for communicating between distributed systems, and is the foundation of the modern web. As a web developer, we all must have a strong understanding of this protocol.
* HTTP allows for communication between a variety of hosts and clients, and supports a mixture of network configurations.
* The protocol is typically http, but it can also be https for secure communications. The default port is 80, but one can be set explicitly. The resource path is the local path to the resource on the server.
* These request verbs are:

  1. GET: fetch an existing resource. The URL contains all the necessary information the server needs to locate and return the resource.
  2. POST: create a new resource. POST requests usually carry a payload that specifies the data for the new resource.
  3. PUT: update an existing resource. The payload may contain the updated data for the resource.
  4. DELETE: delete an existing resource.
* some lesser used verbs that HTTP also supports: HAED, TRACE, OPTIONS.
* Understanding HTTP is crucial for having a clean, simple, and RESTful interface between two endpoints. On a larger scale, it also helps when designing your network infrastructure and providing a great experience to your end users.

<br><br><br>

## What is REST
* REST is acronym for REpresentational State Transfer. It is architectural style for distributed hypermedia systems and was first presented by Roy Fielding in 2000 in his famous dissertation.
* an architectural style and approach to communications often used in web services development.

* A RESTful API is an application program interface (API) that uses HTTP requests to GET, PUT, POST and DELETE data.

<br><br><br>


## Review, Research, and Discussion  
1. Define three related pieces of data in a possible application. 
- MongoDB
- HBase
- Oracle NoSQL Database
2. What is the advantage of an ORM, like Mongoose?
ORMs will shield your application from SQL injection attacks since the framework will filter the data for you! ORMs provide the concept of Database Abstraction which makes switching databases easier and creates a consistent code base for your application.
3. how does the repository pattern compare with an ORM?
THe ORM is an implementation detail of the Repository. The ORM just makes it easy to access the db tables in an OOP friendly way. That's it.
4.  A facade can make a software library easier to use, understand and test, since the facade has convenient methods for common tasks. - make the library more readable, for the same reason.
<br><br><br>

## Document the following Vocabulary Terms
* lifecycle: Application lifecycle is a key way that modern OSs manage resources.
* collections: a form of memory management whereby objects that are no longer referenced are automatically deleted and their resources are reclaimed.
* Repository” design pattern: a kind of container where data access logic is stored.
* mongoose middleware: are functions which are passed control during execution of asynchronous functions. Middleware is specified on the schema level and is useful for writing plugins. Mongoose 4.x has 4 types of middleware: document middleware, model middleware, aggregate middleware, and query middleware. 
* Object Relation Mapping (ORM): a programming technique for converting data between incompatible type systems using object-oriented programming languages.

