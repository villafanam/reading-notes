# Class 3 Notes

## HTML--List 

+ When should you use an unordered list in your HTML document? 

  + When you need to list items in any order  

+ How do you change the bullet style of unordered list items? 

  + Use the `list-style type` CSS property  

  + It lets you change the makers of a list item element 

+ When should you use an ordered list vs an unorder list in your HTML document? 

  + If change the order of a list changes the meaning use an ordered list otherwise use an unordered list 

+ Describe two ways you can change the numbers on list items provided by an ordered list? 

  + `list-style type` CSS property 

  + `type` inline attribute  

## CSS—Box Model 

+ Describe the CSS properties of margin and padding as characters in a story.What is their role in a story titled: “The Box Model”? 

+ List and describe the four parts of an HTML elements box as referred to by the box model. 

  + Content box is the area where content is displayed and has height and width

  + Padding box area is white space between border and content

  + Border box wraps around the content and padding  

  + Margin box is white space that wraps around the content, padding, and border. White space between elements

## JS-- Arrays. Operators and Expressions. Conditionals. Loops. 

+ What data types can you store inside of an Array? 

  + You can store all data types 

``` 

const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]]; 

```

+ Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why? 

  + Yes, you can access by referenceing an element using its index 

  + `Peoeple[0][1] ` 

+ List five shorthand operators for assignment in javascript and describe what they do. 

  + `+=` additions assignment   

    + x = x + y  

  + `-=` subtraction assignment  

     + x = x - y  

  + `*=` multiplication assignment  

     + x = x * y  

  + `/=` division assignment  

    + x = x / y  

  + `%=` reminder assignment  

    + x = x % y 

+ Read the code below and evaluate the last expression and explain what the result would be and why. 

``` 

let a = 10; 
 let b = 'dog'; 
 let c = false; 
 
 // evaluate this 
 (a + c) + b; 

``` 

  + `a + c` is a number  plus a Boolean, the Booleans numerical value will be use which is 1 for false, which give you 11 

  + `11 + ‘dog’` will is a number plus string, when a string is present the whole expression become a string, so 11 is appended to dog to get `‘11dog’` 

+ Describe a real world example of when a conditional statement should be used in a JavaScript program. 

  + Conditional statement should be used to check if a user is logged in on a website 

+ Give an example of when a Loop is useful in JavaScript. 

  + When you want to perform a task or action multiple time or a set number of times, based on a condition you set 

## Things I want to know more about

+ How to use nested loops
+ How to use arrays of arrays (2D arrays)
+ html list styling

© Marco Villafana 201d93