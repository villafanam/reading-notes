# Class 05--Putting it all together

## [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

+ ### What is the single responsibility principle and how does it apply to components? 

  + The idea that a component  should only do one thing and if it ends up growing it should be decomposed into smaller components  

+ ### What does it mean to build a ‘static’ version of your application? 

It means there is no interactivity between components the data doesn’t change 

+ ### Once you have a static application, what do you need to add? 

state 

+ ### What are the three questions you can ask to determine if something is state? 

    1. Is it passed in from a parent via props? If so, it probably isn’t state. 

    2. Does it remain unchanged over time? If so, it probably isn’t state. 

    3. Can you compute it based on any other state or props in your component? If so, it isn’t 

+ How can you identify where state needs to live? 


## [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

+ ### What is a “higher-order function”? 

  + Functions that operate on other functions by taking them in as arguments or returning them 

+ ### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing? 

  + `return m => m > n; `  

  + Returns the value that greater than the variable n  

+ ### Explain how either map or reduce operates, with regards to higher-order functions. 

  + Map return a new array base off the call function used  

  + Reduce returns single value base on the call function used 

## Things I want to know more about

+ How to return functions

© Marco Villafana 301d93