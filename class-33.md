# Context API:

* Context provides a way to pass data through the component tree without having to pass props down manually at every level.

* In a typical React application, data is passed top-down (parent to child) via props, but this can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.

* Context is designed to share data that can be considered “global” for a tree of React components

* Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult.

* Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.

* A React component that subscribes to context changes. This lets you subscribe to a context within a function component.

