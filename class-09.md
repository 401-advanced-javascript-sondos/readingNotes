

* Mongoose -> has 4 types of middleware: document middleware, model middleware, aggregate middleware, and query middleware. 
* Subdocuments :  are documents embedded in other documents. In Mongoose, this means you can nest schemas in other schemas. Mongoose has two distinct notions of subdocuments: arrays of subdocuments and single nested subdocuments.
* Populate Virtuals: In particular, arrays that grow without bound are a MongoDB anti-pattern. Using mongoose virtuals, you can define more sophisticated relationships between documents.
<br><br><br>

## Review, Research, and Discussion  
1. How does route prefixing work with an external routing module?
by importing and exporting, a group of routes may be prefixed by using the prefix option in the attributes array of a group
2. When routing, what’s the difference between app.get('/data/:id') and app.get('/data/:name')?the first params is id and second is name
3. Explain how Express handles routing conflicts?
override the last one of the conflicts routes.
4. What are the ways that a browser can send “data” or request variables to an HTTP server?post and put.

<br><br><br>

## Terms
* Routing:refers to how an application’s endpoints (URIs) respond to client requests.
* Route Prefixing: Route grouping is a concept to make the route function that receive same prefix of different requests.
* request body: data sent by the client to your API.
* Request “Query” :the values that the client browser passed to the server during an HTTP request 
* Request “Params” : is a combination of the keys/values you'll find in Request.Querystring , Request.Form , Request.Cookies , Request.ServerVariables


