# Hooks API

* Hooks are a new addition in React 16.8
* Hooks are functions that let you “hook into” React state and lifecycle features from function components. 
* Hooks don’t work inside classes — they let you use React without classes. (We don’t recommend rewriting your existing components overnight but you can start using Hooks in the new ones if you’d like.)
* React provides a few built-in Hooks like useState. You can also create your own Hooks to reuse stateful behavior between different components.
* The Effect Hook, useEffect, adds the ability to perform side effects from a function component. It serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount in React classes.


## Rules of Hooks
* Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
* Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. 


- Hooks are a way to reuse stateful logic, not state itself.

## What is a Hook? 
A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.

* What does calling useState do? It declares a “state variable”.
* What does useState return? It returns a pair of values: the current state and a function that updates it. 


* useEffect Hook as componentDidMount, componentDidUpdate, and componentWillUnmount combined.

### Basic Hooks:
- useState
- useEffect
- useContext

### Additional Hooks
-UseReducer
- useCallback
- useMemo
- useRef
- useImperativeHandle
- useLayoutEffect
- useDebugValue


* Unlike the setState method found in class components, useState does not automatically merge update objects.
* useContext(MyContext) is equivalent to static contextType = MyContext
