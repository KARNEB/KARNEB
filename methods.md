Functions in JavaScript

A function is a set of statements that take inputs, do some specific computation, and produce output. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can call that function. 

JavaScript supports functions. You must already have seen some commonly used functions in JavaScript like alert(), this is a built-in function in JavaScript. But JavaScript allows us to create user-defined functions also. We can create functions in JavaScript using the keyword function. 

Syntax: The basic syntax to create a function in JavaScript is shown below.

function functionName(Parameter1, Parameter2, ..)
{
    // Function body
}

To create a function in JavaScript, we have to first use the keyword function, separated by name of the function and parameters within parenthesis. The part of the function inside the curly braces {} is the body of the function.

In javascript, functions can be used in the same way as variables for assignments, or calculations.

Function Definition

Before, using a user-defined function in JavaScript we have to create one. We can use the above syntax to create a function in JavaScript. A function definition is sometimes also termed a function declaration or function statement. Below are the rules for creating a function in JavaScript:

Every function should begin with the keyword function followed by,
A user-defined function name that should be unique,
A list of parameters enclosed within parentheses and separated by commas,
A list of statements composing the body of the function enclosed within curly braces {}.


Example:

function calcAddition(number1, number2)
{
	return number1 + number2;
}

In the above example, we have created a function named calcAddition, 

This function accepts two numbers as parameters and returns the addition of these two numbers.
Accessing the function with just the function name without () will return the function object instead of the function result.
There are three ways of writing a function in JavaScript:

Function Declaration: It declares a function with a function keyword. The function declaration must have a function name.

Syntax:

function geeksforGeeks(paramA, paramB) {
    // Set of statements
}

#Function Expression

Function Expression  allows us to create an anonymous function which doesn’t have any function name which is the main difference between Function Expression and Function Declaration. A function expression can be used as an IIFE (Immediately Invoked Function Expression)which runs as soon as it is defined. A function expression has to be stored in a variable and can be accessed using variableName.  With the ES6 features introducing Arrow Function, it becomes more easier to declare function expression.

<script>
	function callAdd(x, y){
		let z = x + y;
		return z;
	}
	console.log("Addition : " + callAdd(7, 4));
</script>

output
Addition : 11

Function Expression: It is similar to a function declaration without the function name. Function expressions can be stored in a variable assignment. 

Syntax:

var geeksforGeeks= function(paramA, paramB) {
    // Set of statements
}

Arrow Function: It is one of the most used and efficient methods to create a function in JavaScript because of its comparatively easy implementation. It is a simplified as well as a more compact version of a regular or normal function expression or syntax.

Syntax:

let function_name = (argument1, argument2 ,..) => expression

Function Parameters

Till now we have heard a lot about function parameters but haven’t discussed them in detail. Parameters are additional information passed to a function. For example, in the above example, the task of the function calcAddition is to calculate the addition of two numbers. These two numbers on which we want to perform the addition operation are passed to this function as parameters. The parameters are passed to the function within parentheses after the function name and separated by commas. A function in JavaScript can have any number of parameters and also at the same time a function in JavaScript can not have a single parameter. 

Calling Functions: After defining a function, the next step is to call them to make use of the function. We can call a function by using the function name separated by the value of parameters enclosed between the parenthesis and a semicolon at the end. Below syntax shows how to call functions in

JavaScript:

functionName( Value1, Value2, ..);

example:

