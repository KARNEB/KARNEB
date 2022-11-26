Javascript provides different types of loops.

while loop
do..while loop
for loop
Note: Javascript also includes for..in, for..each, for..of loop though they are beyond the scope of this course.

while loop
A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.
while(condition){
 do..this;
}

The condition/expression we pass inside the parenthesis of the while loop must evaluate to true otherwise the statements we write inside the block of the while loop will not be executed.
Example:
<script>
// working while loop example
let i = 0;
while( i < 5){
document.write('Hello World'+'<br/>');
i++; // necessary to increase the iterator value
}
</script>
do..while loop
do while loop is similar to while loop with the only difference that it checks for the condition after executing the statements. I don’t matter if the condition inside the while parenthesis is true or not the loop will run at least once.

do
{
    statements..
}
while (condition);
Example:
  <script>
// do while loop
// JavaScript program to illustrate do-while loop
	let x = 21;
	
	do
	{
		document.write("Value of x: " + x + "<br />");
		x++;
	} while (x < 20);
	
</script>
    
Output:
Value of x: 21
   #For Loop
For loop provides a concise way of writing the loop structure. Unlike a while loop, a for statement consumes the initialization, condition and increment/decrement in one line thereby providing a shorter, easy to debug structure of looping.
    
    for (initialization condition; testing condition;  increment/decrement) {
  do..this;
    
    Initialization condition: Here, we initialize the variable in use. It marks the start of a for loop. An already declared variable can be used or a variable can be declared, local to loop only.
Testing Condition: It is used for testing the exit condition for a loop. It must return a boolean value. It is also an Entry Control Loop as the condition is checked prior to the execution of the loop statements.
Statement execution: Once the condition is evaluated to true, the statements in the loop body are executed.
Increment/ Decrement: It is used for updating the variable for next iteration.
Loop termination: When the condition becomes false, the loop terminates marking the end of its life cycle.
}
    Example:
    <script>
// for loop
for(let i = 0; i < 5;i++){
document.write('Value of i is: ' + i +'<br/>' );
}
</script>
Output:

Value of i is: 0
Value of i is: 1
Value of i is: 2
Value of i is: 3
Value of i is: 4
      
