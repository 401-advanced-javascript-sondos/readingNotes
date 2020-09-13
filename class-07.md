## Using middleware
* Express is a routing and middleware web framework that has minimal functionality of its own: An Express application is essentially a series of middleware function calls.
* Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.
* Middleware functions can perform the following tasks:
  1. Execute any code.
  2. Make changes to the request and the response objects.
  3. End the request-response cycle.
  4. Call the next middleware function in the stack.

* An Express application can use the following types of middleware:
  1. Application-level middleware
  2. Router-level middleware
  3. Error-handling middleware
  4. Built-in middleware
  5. Third-party middleware
  

<br><br><br>

## Routing:
* Routing refers to how an application’s endpoints (URIs) respond to client requests. 
* 
<br><br><br>

## Review, Research, and Discussion  
1. What’s the difference between PUT and PATCH?
The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

2. Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
Nock, MockServer, Beeceptor

3. Compare and contrast SOAP and ReST
- The difference is: SOAP is a XML-based message protocol, while REST is an architectural style.
- SOAP uses WSDL for communication between consumer and provider, whereas REST just uses XML or JSON to send and receive data. 
- SOAP invokes services by calling RPC method, REST just simply calls services via URL path.

<br><br><br>

## Document the following Vocabulary Terms
* SOAP: Simple Object Access Protocol ,SOAP is an XML-based protocol for accessing web services over HTTP.
* ReST Verbs : REST verbs specify an action to be performed on a specific resource or a collection of resources.(GET,POST,PUT,DELETE)
* CRUD Verbs : Create, Read, Update, and Delete.
* Swagger:is a set of rules (in other words, a specification) for a format describing REST APIs. ... As a result, it can be used to share documentation among product managers, testers and developers, but can also be used by various tools to automate API-related processes.
