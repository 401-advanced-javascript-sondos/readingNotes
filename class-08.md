## Routing:
* Routing refers to how an application’s endpoints (URIs) respond to client requests. 
* In fact, the routing methods can have more than one callback function as arguments. With multiple callback functions, it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback.
<br> <br>

## Route paths :
* Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.
`app.get('/ab+cd', function (req, res) {
  res.send('ab+cd')
})`
- This route path will match abcd, abbcd, abbbcd, and so on.
<br><br><br>

## Route parameters
* Route parameters are named URL segments that are used to capture the values specified at their position in the URL.
`Route path: /users/:userId/books/:bookId
Request URL: http://localhost:3000/users/34/books/8989
req.params: { "userId": "34", "bookId": "8989" }`




<br><br><br>

## Review, Research, and Discussion  
1. Name 3 real world use cases where you’d want to change the request with custom middleware?
2. True or false: The route handler is middleware? true and false,"These routing methods specify a callback function (sometimes called “handler functions”) called when the application receives a request to the specified route (endpoint) and HTTP method."
3. In what ways can a middleware function end the process and send data to the browser? by using res.method (method maybe send ,end ...).
4. At what point in the request lifecycle can you “inject” middleware?
 before the start of the request lifecycle.
 when a reponse or some callbacks are called twice.

 <br><br><br>

## Terms
* Middleware:are functions that have access to the request object (req), the response object (res),and the next middleware function in the - application’s request-response cycle.
* Request Object:  represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so ...
* Response Object : is used to send output to the user from the server.
* Application Middleware : is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.
* Routing Middleware : determining how an application responds to a client request to a particular endpoint.

