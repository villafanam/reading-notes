# Class 08--APIs

## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

+ ### What does REST stand for? 

  + Representational State Transfer 

+ ### REST APIs are designed around a ____. 

  + resource 

+ ### What is an identifier of a resource? Give an example. 

  + URI—Uniform Resource Identifier  

  + https://adventure-works.com/orders/1 

+ ### What are the most common HTTP verbs? 

  + GET, POST, PUT, PATCH, and DELETE. 

+ ### What should the URIs be based on? 

  + Should be base on nouns (the resource) and not verbs (the operation on the resource) 

+ ### Give an example of a good URI. 

  + https://adventure-works.com/orders // Good 

  + https://adventure-works.com/create-order // Avoid 

+ ### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? 

  + It means it spend multiple requests to find all the data it requires 

+ ### What status code does a successful GET request return? 

  + 200 (OK) 

+ ### What status code does an unsuccessful GET request return? 

  + 404 (Not Found) 

+ ### What status code does a successful POST request return? 

  + 201 (Created) 

+ ### What status code does a successful DELETE request return? 

  + 204 (No Content) 

## Things I want to know more about

+ How to use PUT?

© Marco Villafana 301d93