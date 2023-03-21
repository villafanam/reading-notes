# Class 27--useState() Hook

## [Thinking in React](https://react.dev/learn/thinking-in-react)

+ Summarize the five steps of thinking in react. 

  1. Break the UI into components hierarchy 
  2. Build a static version in React 
  3. Find the minimal but complete representation of UI state 
  4. Identify where your state should live 
  5. Add inverse data flow 

## [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)

+ What is one reason a local variable isn’t sufficient for managing a React component? 

  + Because local variable hava scope of whatever component they are in. They can be use beyond the componenet they are contained in 

+ What is the argument to the useState hook, and what are the two parts of its return array? 

  + Argument: the initial value of your state variable 
  + Return array: the current state and the function to update it. 

+ How can Component A access state from Component B? 

  + You use a Hook to access it	 

## Things I want to know more about

+ How to implement custom hooks

© Marco Villafana 401d51