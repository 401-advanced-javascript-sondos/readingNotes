
## Securing Passwords with Bcrypt Hashing Function
* Cryptographic hash algorithms MD5, SHA1, SHA256, SHA512, SHA-3 are general purpose hash functions, designed to calculate a digest of huge amounts of data in as short a time as possible. Hashing is the greatest way for protecting passwords and considered to be pretty safe for ensuring the integrity of data or password.
* The benefit of hashing is that if someone steals the database with hashed passwords, they only make off with the hashes and not the actual plaintext passwords.
* PROBLEMS WITH CRYPTOGRAPHIC HASH ALGORITHM:
  - Brute Force attack.
  - Hash Collision attack.

### What is JSON Web Token?
- JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.  

### When should you use JSON Web Tokens?
1. Authorization
2. Information Exchange

### What is the JSON Web Token structure?
In its compact form, JSON Web Tokens consist of three parts separated by dots (.), which are:
1. Header
2. Payload
3. Signature
  

<br><br><br>

## Review, Research, and Discussion  
1. Explain what a “Singleton” is (in Computer Science terms)?
- A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object.
2. Explain how the Singleton pattern can be used with Node modules, specifically with classes.
- In node if you need a singleton, for instance to use the same ORM/DB instance across various files in your server layer, you can stuff the reference into a global variable. Just write a module that creates the global var if it doesn't exist, then returns a reference to that.


<br><br><br>

## Terms
* Router Middleware : A middleware you can apply to your Redux store to capture dispatched actions created by the action creators. It will redirect those actions to the provided history instance.
* Dynamic Module Loading :is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.
* Singleton Pattern : is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system.
* CRUD -> REST Method Matches : 
  - Create : post
  - read : get
  - update : put
  - delete : delete
* Mock Testing : is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules
 