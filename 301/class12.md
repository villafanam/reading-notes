# Class 12--CRUD

## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

+ ### In your own words, describe what each group of status code represents: 

  + 100’s = request received and will try and comply 

  + 200’s = success request accepted 

  + 300’s = request is unavailable 

  + 400’s = invalid request 

  + 500’s = overwhelmed server or unreachable server  

+ ### What is a status code 202? 

  + Accepted - valid request 

+ ### What is a status code 308? 

  + Permanent redirect - use another URL 

+ ### What code would you use if an update didn’t return data to a client? 

  + 204 

+ ### What code would you use if a resource used to exist but no longer does? 

  + 410 

+ ### What is the ‘Forbidden’ status code? 

  + 403 no permissions to access the resource  

## [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

+ ### Why do we need to pull our MongoDB database string out of our server and put it into our .env? 

  + Because it exposes your MongoDB password 

+ ### What is middleware? 

 

+ ### What does app.use(express.json()) do? 
  + let you parse JSON strings 

+ ### + ### What does the /:id mean in a route? 

  + Path parameter 

+ ### What is the difference between PUT and PATCH? 

  + PUT requires the whole resource with the changes and PATCH only need the changes  

+ ### How do you make a default value in a schema?	 

Use `default:` in the option object  

+ ### What does a 500 error status code mean? 

  + Internal server Error  - unreachable service 

+ ### What is the difference between a status 200 and a status 201? 

  + 200 – everything was successful  

  + 201 – successfully created resource  

 

## Things I want to know more about

+ When to use default values in a schema?

© Marco Villafana 301d93