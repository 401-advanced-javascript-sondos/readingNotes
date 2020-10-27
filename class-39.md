# Redux Toolkit

* The Redux Toolkit package is intended to be the standard way to write Redux logic. 
*  Redux Toolkit can help you make your Redux code better.
* `configureStore()`: wraps createStore to provide simplified configuration options and good defaults. and add midddlewire you want
* `createReducer()`: that lets you supply a lookup table of action types to case reducer functions, rather than writing switch statements. 
* `createAction()`: generates an action creator function for the given action type string
* `createSlice()`: accepts an object of reducer functions, a slice name, and an initial state value, and action.
* `createAsyncThunk`: accepts an action type string and a function that returns a promise and use thunk
* `createEntityAdapter`: generates a set of reusable reducers and selectors to manage normalized data in the store.



## Using Create React App
`npx create-react-app my-app --template redux`


## An Existing App
`npm install @reduxjs/toolkit`