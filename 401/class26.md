# Class 26--Component Based UI

## [React Quick Start](https://react.dev/learn)

+ What are the building blocks of a React app?

  + React is made up of elements or object that determine what you see on the screen

+ What is the difference between an HTML element and a React component?

  + HTML elements are what determine behavior and  what you see when a website is rendered  

  + React components are made up of HTML elements, CSS, and JavaScript to make reusable elements or components  

+ What is JSX and why do we use it?

  + JavaScript syntax extension for JavaScript that lets you write HTML inside a JavaScript file

+ Describe the process of embedding JavaScript expressions in JSX.

  + You just use JavaScript inside of `{ }` curly braces

+ Does React or JSX have any special features for iteration or conditional logic?

  + JSX can use loop and if statements just like JavaScript

+ How does React know to respond to a user’s inputs?

  + It uses event handlers, functions that will be triggered in by user interaction like clicking with the use of the `onClick()` event handler

+ What word indicates that a React component manages data with a Hook?

  + `use`  

+ How can two react components share data?

  + By passing `props` between the two components  

## [Render and Commit](https://react.dev/learn/render-and-commit)

+ What are the three steps of refreshing a React UI?

    1. Triggering a render

    2. Rendering component  

    3. Committing to the DOM

+ How do you trigger updates to a component after the initial render?

  + You the `set` function to update its state and trigger a render

+ Does React recreate DOM nodes on every re-render?

  + No, React only changes the DOM nodes if there are differences between the renders  

+ After React has updated the DOM, what still needs to happen before the user sees the change?

  + The browser will paint the screen (browser rendering)

## Things I want to know more about

+ How to implement custom hooks

© Marco Villafana 401d51
