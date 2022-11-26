
#Conditional Statements in JavaScript
The conditional statements included in the JavaScript code assist with decision making, based on certain conditions. The condition specified in the conditional statement can either be true or false. The conditional statements execute the associated piece of code only if the condition is true. We have four types of conditional statements in JavaScript:

An if statement executes a specified code segment if the given condition is ''true.''
An else statement executes the code associated with the else if the given if condition is ''false.''
An else if statement specifies a new condition for testing when the first if condition is ''false.''
A switch-case statement specifies multiple alternative code blocks for execution and executes these cases based on certain conditions.

 
The If Conditional Statement
Remember that the conditional if statement specifies a JavaScript code for execution only if the given condition is ''true.''

Here's the syntax:

if (condition)

{

//code to get executed when the above specified condition is true

}

Now here's an example:

if (age>=18)
{
eligibility= 'Votable age';
}
The if statement here checks if the variable age is greater than or equal to 18. If it's greater than or equal to 18, it assigns ''Votable age'' to the variable eligibility. For age values less than 18, the condition fails and the code associated with the if statement will not be executed.

The Else Conditional Statement
When the condition inside the if statement is false, the code associated with the else statement gets executed.

Here's the syntax:

if (condition)

{

//code to get executed when the condition is true

}

else

{

//code to get executed when the 'if' condition fails

}

Here's an example:

if (age>=18)
{
eligibility= 'Votable age';
}
else
{
eligibility='Not votable age';
}
If the value of the age variable is ≥ 18, the code associated with the if condition is executed. On the other hand, if the age variable's value is < 18, the code associated with the else statement is executed and ''non votable age'' is assigned to the variable eligibility.

The Else-If Conditional Statement
When the first condition fails, the else if allows the program to specify some new condition or conditions.

Here's our syntax:

if (condition_one)

{

//code to execute if condition_one is true

}

else

{

//code to execute if the condition_one is false

}

else if (condition_two)

{

//code to execute if the condition_one fails but the condition_two is true

}

#The JavaScript Switch Statement
Use the switch statement to select one of many code blocks to be executed.

Syntax
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
This is how it works:

The switch expression is evaluated once.
The value of the expression is compared with the values of each case.
If there is a match, the associated block of code is executed.
If there is no match, the default code block is executed.
Example
The getDay() method returns the weekday as a number between 0 and 6.

(Sunday=0, Monday=1, Tuesday=2 ..)

This example uses the weekday number to calculate the weekday name:

switch (new Date().getDay()) {
  case 0:
    day = "Sunday";
    break;
  case 1:
    day = "Monday";
    break;
  case 2:
     day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
    break;
  case 5:
    day = "Friday";
    break;
  case 6:
    day = "Saturday";
}

