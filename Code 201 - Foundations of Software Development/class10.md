# Class 10 Notes

## [What Went Wrong? Trubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

- Name some key differences between a Syntax Error and a Logic Error. 

  - Syntax errors – spelling or formatting errors 

  - Logic errors – errors where the syntax is correct but code run and give the incorrect results  

- List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them. 

``` 

While (var1 || var2 && var 3 || var2 && var1 || var3) 
{ 
    Code... 
} 

``` 
- This is a logic error since it counts the ANDs expression as before the OR’s expressions. So I only need to add parathesis to OR expressions. see blow

```
While ( (var1 || var2) && (var 3 || var2) && (var1 || var3) ) 
{ 
    Code... 
} 

``` 

- How will this topic continue to influence your long-term goals? 

  - It will change mindset to keep in mind that testing regularly will lead to less error in the long run  

## [The JavaScript Debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)

- How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development? 

  - The debugger let you run code line by line starting from a starting point you chose 

- Define what a breakpoint is. 

  - It the point where you want to pause the cod execution 

- What is the call stack? 

  - Shows you what code was executed to get to the current line 

## Things I want to know more about

+ How to use the debugger in VS Code
+ How to do unit testing


© Marco Villafana 201d93