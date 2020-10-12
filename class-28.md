# Component Composition:

*  component can only be in one stage at a time
* It starts with mounting and moves onto updating. It stays updating perpetually until it gets removed from the virtual DOM. Then it goes into the unmounting phase and gets removed from the DOM.
* A higher-order component is a function that takes a component and returns a new component.
*  setState is asynchronous. This means state won’t update exactly after you call setState and this can lead to some aggravating behavior which we will hopefully now be able to avoid!
* The React context API allows you to create global context objects that can be given to any component you make. This allows you to share data without having to pass props down all the way through the DOM tree.
* in React 16.3, certain lifecycle methods were deprecated, in React 16.6 we now get async components, and in 16.7 we get hooks which aim to replace class components entirely.


## props.children
* this.props.children does is that it is used to display whatever you include between the opening and closing tags when invoking a component.


