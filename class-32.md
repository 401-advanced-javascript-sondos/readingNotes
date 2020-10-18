# Custom Hooks

* A custom Hook is a JavaScript function whose name starts with ”use” and that may call other Hooks. 
* a custom Hook doesn’t need to have a specific signature. We can decide what it takes as arguments, and what, if anything, it should return. In other words, it’s just like a normal function. Its name should always start with use so that you can tell at a glance that the rules of Hooks apply to it.
* Extract duplicated logic from components
* Share common functionality
* Take advantage of useEffect lifecycle
* We make custom hooks, to make our code cleaner and single liner on final usage. It must be not redundant or to keep it DRY.
* 


## React Hooks with Async-Await
- We cannot use ‘async’ keyword with ‘useEffect’ callback method. It will result in race conditions.
- so we should fetch our data from an API then updating our ‘setResult’ state
so React.useEffect method will only run when our ‘state’ got change.
 