# Debugging
 
 ## ORDER OF EXECUTION
It helps to know how scripts are processed in order to find the source of an error.

## EXECUTION CONTEXTS 
Every statement in a script lives in one of three
execution contexts:

- GLOBAL CONTEXT
Code that is in the script, but not in a function.
There is only one global context in any page.

- FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.

- EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function
called eva l () (which is not covered in this book). 

## EXECUTION CONTEXT & HOISTING 
Each time a script enters a new execution context, there are two phases of activity:

1: PREPARE      2: EXECUTE 

## UNDERSTANDING SCOPE 
Functions in JavaScript are said to have lexical scope. They are linked to the object they were defined within. So, for each execution context, the scope is the current execution context's variables object.

## UNDERSTANDING ERRORS
if a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. 

## ERROR OBJECTS
Error objects can help you find where your mistakes are and browsers have tools to help you read them. 

When an Error object is created, it will contain the following properties: 
-name: Type of execution

-message: Description

-file Number: Name of the JavaScript file

-line Number: Line number of error

There are seven types of built-in error objects in
JavaScript:

- Error

- Syntax Error

- Generic error 

- Reference Error 

- Type Error

- Range Error

- URI Error

- Eval Error


## HOW TO DEAL WITH ERRORS 
- There are two things we can do with the errors:
1: DEBUG THE SCRIPT TO FIX ERRORS 

2: HANDLE ERRORS GRACEFULLY

## A DEBUGGING WORKFLOW 
- WHERE IS THE PROBLEM? 
1. Look at the error message
2. Check how far the script is running. 
3. Use breakpoints where things are going wrong

- WHAT EXACTLY IS THE PROBLEM? 
1. When you have set breakpoints, you can see if the variables around them have the values you would expect them to. If not, look earlier in the script.
2. Break down I break out parts of the code to test smaller pieces of the functionality. 
3. Check the number of parameters for a function, or the number of items in an array.

## BROWSER DEV TOOLS & JAVASCRIPT CONSOLE
- The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. 

for example, in CHROME:
On a PC, press the F12 key or:
1. Go to the options menu (or three line menu icon)
2. Select Toots or More tools.
3. Select JavaScript Console or Developer Tools
On a Mac press Alt + Cmd + J. Or:
4. Go to the View menu.
5. Select Developer.
6. Open the JavaScript Console or Developer Tools
option and select Console. 

## BREAKPOINTS 
You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time. 

## THROWING ERRORS
If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them. 
To create your own error, you use the following line:
- throw new Error( 'message ') ; 





