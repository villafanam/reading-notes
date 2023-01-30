# Passing Functions as Props

## [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

+ ### What does `.map()` return? 

  + New array 

+ ### If I want to loop through an array and display each value in JSX, how do I do that in React? 

```  

const numbers = [1, 2, 3, 4, 5]; 
const listItems = numbers.map((number) =>  <li>{number}</li>); 

``` 

+ ### Each list item needs a unique ____. 

  + key 

+ ### What is the purpose of a key? 

  + Helps identifies which items have changed, are added or removed 

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

+ ### What is the spread operator? 

  + `(…)` JS syntax use to expand an iterable object(array) into the list of arguments 

+ ### List 4 things that the spread operator can do. 

    + Copy an array 

    + Combine arrays 

    + Adding an item to a list 

    + Combining objects 

+ ### Give an example of using the spread operator to combine two arrays. 

  + `NewArr = (...arr1,...arr2)` 

+ ### Give an example of using the spread operator to add a new item to an array. 

  + `NewArr = (arr,...item)` 

+ ### Give an example of using the spread operator to combine two objects into one. 

  + `const objectThree = {...objectOne, ...objectTwo}` 
 
## Things I want to know more about

+ How to use `reduce()`?

© Marco Villafana 301d93