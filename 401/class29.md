# Class 29--Advanced State with Reducers

## [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

+ What is the motivation for adding a reducer?

  + To consolidate all the state update logic outside components into a single function  

+ What are actions in the context of a reducer? How are they different than setting state directly?

  + Actions are what the user just did (dispatching actions) instead of telling react what to do (setting state)  

+ What common list operation is useReduce named for, and why?

  + `reduce()` which lets you take an array and “accumulate” a single value out of many. Reducers take the state so far and the action and return the next state. They accumulate actions over time into state

+ When should you switch from useState to useReducer?

  + When you encounter bugs due to incorrect state updates or want more structure in the code  

## Things I want to know more about

+ How to write reducer functions

© Marco Villafana 401d51
