# Using combineReducers

*  Multiple slice reducers can respond to the same action, independently update their own slice as needed, and the updated slices are combined into the new state object.
* Because this pattern is so common, Redux provides the combineReducers utility to implement that behavior. It is an example of a higher-order reducer, which takes an object full of slice reducer functions, and returns a new reducer function.
*  combineReducers is simply a utility function to simplify the most common use case when writing Redux reducers.
* n order to assemble the new state tree, combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed.
* You can use it at all levels of your reducer structure, not just to create the root reducer.
* The state produced by `combineReducers()` namespaces the states of each reducer under their keys as passed to `combineReducers()`.
* you can change the name of reducer in combine as follow:
  --- For example, you may call `combineReducers({ todos: myTodosReducer, counter: myCounterReducer })` for the state shape to be `{ todos, counter }`.
* the benfiet of using combine reducer : 
   - it will never return nudefined.
   - it will give first one if it not recognized.  




## Term	
- immutable state :	is an object whose state cannot be modified after it is created. This is in contrast to a mutable object (changeable object), which can be modified after it is created.
- time travel in redux: The Redux DevTools records dispatched actions and the state of the Redux store at every point in time. ... This makes it possible to inspect the state and travel back in time to a previous application state without reloading the page or restarting the app.
- action creator: a function that returns an action object.
- dispatch: a function of the Redux store. You call store. dispatch to dispatch an action. This is the only way to trigger a state change.

