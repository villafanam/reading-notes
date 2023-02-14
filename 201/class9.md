# Class 9 Notes

## [HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

- Why are forms so important in web development? 

  - They make gathering data from user input easier and more efficient  

- When designing a form, what are some key things to keep in mind when it comes to user experience? 

  - Logical order the form will be filled  

  - Layout  

- List 5 form elements and explain their importance. 

  - `<form>` the container for the form and its elements  

  - `<label>` caption for the item.  usually associated with `<input>` 

  - `<input>` element use to create interactive controls for forms to get data form the user 

  - `<button>` interactive element activated by user (ex. Clicked) 

  - `<fieldset>` element used to group other form elements together like the labels and input elements 

  ## [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) [- Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

- How would you describe events to a non-technical friend? 

  - Event is a thing that happens when triggered by something like a condition or button 

- When using the addEventListener() method, what 2 arguments will you need to provide? 

  - Type - a string of the event type 

  - Listener – the object the receives a notification when an event occurs  

- Describe the event object. Why is the target within the event object useful? 

  - They are actions or occurrences that happen are triggered system you are programing. The target references the object that had an event trigged on it which will let you access objects properties  

- What is the difference between event bubbling and event capturing? 

  - Event bubbling fires first form the innermost element targeted and out form there 

  - Event capturing fires from the least nested element and then the on successively more nested elements until the target is reached 

    - Event capture is disabled by default.  

    - To enable pass capture option in `addEventListener()` 

    - `document.body.addEventListener('click', handleClick, { capture: true });` 

## Things I want to know more about

+ How to use a drop down list
+ how to make use events to make changes using a drop down list


© Marco Villafana 201d93