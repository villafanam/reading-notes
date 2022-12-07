# Class 6 Notes

## [JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

+ How would you describe an object to a non-technical friend you grew up with? 

  + It is like a collection of items where some items can perform task like people and jobs.  

+ What are some advantages to creating object literals? 

  + They let you store and create data in one place since you can make method for them 

+ How do objects differ from arrays? 

  + Objects represent things with properties while arrays create and store list of data in a single varible  

+ Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation. 

  + When a objects property is held in variable you would need to use bracket notation to access the value 

+ Evaluate the code below. What does the term this refer to and what is the advantage to using this? 

  + `this` is referencing the object it is in, in this case the dog object.  `this` allow you to use the same method definition for every object you create. 

```
const dog = { 
  name: 'Spot', 
  age: 2, 
  color: 'white with black spots', 
  humanAge: function (){ 
    console.log(`${this.name} is ${this.age*7} in human years`); 
  } 
} 
``` 
## [Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

+ What is the DOM? 

  + programming interface for web document  

  + Represents the document as nodes and objects so programming languages can interact with the page 

+ Briefly describe the relationship between the DOM and JavaScript. 

  + DOM turn the web page into node and object so JavaScript can interact or manipulate it

## Things I want to know more about

+ How to make elements using the DOM
+ How to use classes


© Marco Villafana 201d93