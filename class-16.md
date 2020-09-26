## Event-Driven Programming in Node.js

* Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision.
* Event-Driven Programming makes use of the following concepts:

 - An Event Handler is a callback function that will be called when an event is triggered.
 - A Main Loop listens for event triggers and calls the associated event handler for that event.

### EventEmitter
`const EventEmitter = require('events').EventEmitter;
const chatRoomEvents = new EventEmitter;

function userJoined(username){
  // Assuming we already have a function to alert all users.
  alertAllUsers('User ' + username + ' has joined the chat.');
}

// Run the userJoined function when a 'userJoined' event is triggered.
chatRoomEvents.on('userJoined', userJoined);`


### Removing Listeners
* To remove event listeners in EventEmitter we can use the removeListener or removeAllListeners method.
* `chatRoomEvents.removeListener('message', displayMessage);`


## Review, Research, and Discussion
1. Why is access control important?
- The goal of access control is to minimize the risk of unauthorized access to physical and logical systems.
2. application that would need access control.
- Personnel Management.
3. What is a role used for?
- it use to make permissions to user if they can use it or not 


<br><br><br>

## Terms:
* Authorization:  is the process of giving someone permission to do or have something.
* Role Based Access Control : is a method of restricting network access based on the roles of individual users within an enterprise. 
* Capabilities :It refers to a value that uniquely references an object along with an associated set of access rights
