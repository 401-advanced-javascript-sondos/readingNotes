# Application State with Redux

* State management is absolutely critical in providing users with a well-crafted experience with minimal bugs.
* Redux provides a solid, stable and mature solution to managing state in your React application. Through a handful of small, useful patterns, Redux can transform your application from a total mess of confusing and scattered state, into a delightfully organized, easy to understand modern JavaScript powerhouse.
* In larger apps with a lot of moving pieces, state management becomes a huge concern. Redux ticks that off quite well without performance concerns or trading off testability.
* A lot of developers love Redux for the developer experience that comes with it.
* Using Redux you will get good features; include logging, hot reloading, time travel, universal apps, record and replay — all without doing so much on your end as the developer. 


## Testing redux reducers with Jest

* Usually reducer consists of initial state and switch statement to handle every action. I like to break down my store into different sub-stores and have separate reducers for each sub-store.
* Sometimes one switch/case may handle few actions, because the business logic is the same and outcome should be the same. Some example GET_POST and UPDATE_POST should update the same store and produce same outcome.
* `import reducer from './getPostReducer'`;
* ` describe('post reducer', () => {
  it('should return the initial state', () => {
    expect(reducer(undefined, {})).toEqual({});
  }); `



