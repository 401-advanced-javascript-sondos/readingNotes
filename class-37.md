# Using combineReducers

*  Multiple slice reducers can respond to the same action, independently update their own slice as needed, and the updated slices are combined into the new state object.
* Because this pattern is so common, Redux provides the combineReducers utility to implement that behavior. It is an example of a higher-order reducer, which takes an object full of slice reducer functions, and returns a new reducer function.
*  combineReducers is simply a utility function to simplify the most common use case when writing Redux reducers.
* n order to assemble the new state tree, combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed.
* You can use it at all levels of your reducer structure, not just to create the root reducer.
