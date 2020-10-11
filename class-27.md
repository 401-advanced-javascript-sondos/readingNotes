## Workings of `setState()`
setState() is the only legitimate way to update state after the initial state setup. Let’s say we have a search component and want to display the search term a user submits.

* When working with setState(), these are the major things you should know:

  1. Update to a component state should be done using setState()
  2. You can pass an object or a function to setState()
  3. Pass a function when you can to update state multiple times
  4. Do not depend on this.state immediately after calling setState() and make use of the updater function instead.

## Components and Props
* When React sees an element representing a user-defined component, it passes JSX attributes and children to this component as a single object. We call this object “props”.
* We call ReactDOM.render() with the <Welcome name="Sara" /> element.
* React calls the Welcome component with {name: 'Sara'} as the props.
* Components can refer to other components in their output. This lets us use the same component abstraction for any level of detail. A button, a form, a dialog, a screen: in React apps, all those are commonly expressed as components.

## Handling Events
Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:

* React events are named using camelCase, rather than lowercase.
* With JSX you pass a function as the event handler, rather than a string.