# JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task.

* Example: 

function myFunction(p1, p2) {

  return p1 * p2;   // The function returns the product of p1 and p2

}

## JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
The code to be executed, by the function, is placed inside curly brackets: {}

* Example:

function name(parameter1, parameter2, parameter3) {

  // code to be executed

}

## Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

1. When an event occurs (when a user clicks a button)
2. When it is invoked (called) from JavaScript code
3. Automatically (self invoked)

## Function Return
When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller".

## Why Functions?
You can reuse code: Define the code once, and use it many times.
You can use the same code many times with different arguments, to produce different results.

## Local Variables
Variables declared within a JavaScript function, become LOCAL to the function.
Local variables can only be accessed from within the function.

* Example:
// code here can NOT use carName

function myFunction() {

  var carName = "Volvo";

  // code here CAN use carName

}

// code here can NOT use carName
