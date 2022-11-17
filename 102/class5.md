# Class 5 Notes

## CSS 

+ Cascading Style Sheets (CSS) use to style HTML 

+ Consists of many different selectors and attributes  

+ Inline CSS bad practice 

+ Rule based language—by selecting groups of styles and applying them on an elements or group of elements you define rules 

+ `h1 {`
        `color: red;`  
        `font-size: 5em;` 
    `}` 

  + Selector is h1 it selects all `<h1>` HTML elements 

  + { } hold declarations made up of properties and values 

  + Color is a property with value of red 

  + Font-size property with value of 5em 

+ `Selector {`
    `Property: value;` 
`}` 

### External CSS 

+ Best practice to use style sheet files 

+ External sheets can change the look of a website by changing one file. 

+ Can be written in any text editor and must be save as a .css extension 

+ Should not contain any HTML tags 

`body { 
  background-color: lightblue; 
}` 

`h1 { 
  color: navy; 
  margin-left: 20px; 
}` 

### Internal CSS 

+ Used when one single HTML page has a unique style 

`<html> `

  `<head>` 

    <style>
      body { 
        background-color: linen; 
      } 

      h1 { 
        color: maroon; 
        margin-left: 40px; 
      }

    </style> 

  `</head>` 

  `<body>` 

    <h1>This is a heading</h1> 
    <p>This is a paragraph.</p> 

  `</body>`

`</html>`

### Inline CSS 

+ Used to apply a unique style for a single element 

+ By adding the style attribute to the element 

+ Stylel attribute can contain any CSS propetry 

`<h1 style="color:blue;text-align:center;">This is a heading</h1>` 

`<p style="color:red;">This is a paragraph.</p>` 

 
## Things I want to know more about 

+ how to center images
+ how to get text to wrap around images
+ hot to change fonts


©Marco Villafana 102d45