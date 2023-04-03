# Class 36--Application State with Redux

## [Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)

+ What is the first principle of Redux?

  + Is whether your app is a simple or a complex application where you will use a single JavaScript object to hold the whole state  

+ What is a store and what do we use our reducers for within that store?

  + Store holds the current app state object and lets you dispatch actions. The reducers determine how state is updated

+ Name three Redux store methods given to us by createStore and describe their use.

  + `getState()` - it get the current state of the Redux store

  + `dispatch()` - let you dispatch actions to change the state of the application

  + `subscribe()` - lets you register a callback that is called any time an action is dispatched, so you can update the UI of the application

+ Explain to a non-technical recruiter what combineReducers() does and why it is useful.

  + It generates a simple reducer that calls many reducers to manage parts of the tree

  + It's like a store manager calling more managers to help manage the store

## Things I want to know more about

+ When to use Redux

© Marco Villafana 401d51
