# Redux - Asynchronous Actions

* When you call an asynchronous API, there are two crucial moments in time:
 -  the moment you start the call.
 -  the moment when you receive an answer (or a timeout).
* to dispatch API request we need  three different kinds of actions:
  1. an action tell the reducer that the action start
  2. an action tell the reducer the action is done.
  3. an action tell the reducer about falier actions.
`{ type: 'FETCH_POSTS_REQUEST' }
{ type: 'FETCH_POSTS_FAILURE', error: 'Oops' }
{ type: 'FETCH_POSTS_SUCCESS', response: { ... } }`

* For every list of items, you’ll want to store `isFetching` to show a spinner, `didInvalidate` so you can later toggle it when the data is stale, `lastUpdated` so you know when it was fetched the last time, and the items themselves.


##  Redux Thunk middleware
* It comes in a separate package called redux-thunk

* Ways to orchestrate asynchronous actions in Redux:
   * `redux-promise` or `redux-promise-middleware` to dispatch Promises instead of functions. 
   *  `redux-observable` to dispatch Observables.
   * `redux-saga` middleware to build more complex asynchronous actions.
   *  `redux-pack` middleware to dispatch promise-based asynchronous actions.
   *  write a custom middleware to describe calls to your API.
   * Redux Thunk middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. The inner function receives the store methods dispatch and getState as parameters.
   <br><br>

   ![img](https://miro.medium.com/max/799/0*l66us_4-3WiL6af9.png)


   ## Terms:
   * store:A store holds the whole state tree of your application. It’s just an object with a few methods on it.
   * combined reducers: The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore .







 