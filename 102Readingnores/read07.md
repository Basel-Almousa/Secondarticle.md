# Functions in JS
+ The control flow is the order in which the computer executes statements in a script.

+ Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 
+ A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.

+ **For example**, the above excerpt might be inside a function that runs when the user clicks the Submit button for the form. The function could also include a loop, which iterates through all of the fields in the form, checking each one in turn. Looking back at the code in the if and else sections, the lines promptUser and submitForm could also be calls to other functions in the script. As you can see, control structures can dictate complex flows of processing even with only a few lines of code.

+ Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

# Function in JS
+ A JavaScript function is a block of code designed to perform a particular task.

+ A JavaScript function is executed when "something" invokes it (calls it).
+ A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

+ Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

+ The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

+ The code to be executed, by the function, is placed inside curly brackets: {}

## Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

+ When an event occurs (when a user clicks a button)
+ When it is invoked (called) from JavaScript code
+ Automatically (self invoked)

## Function Return
+ When JavaScript reaches a return statement, the function will stop executing.

+ If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

+ Functions often compute a return value. The return value is "returned" back to the "caller"

## Javascript Operators
+ JavaScript includes operators as in other languages. An operator performs some operation on single or multiple operands (data value) and produces a result. For example 1 + 2, where + sign is an operator and 1 is left operand and 2 is right operand. + operator adds two numeric values and produces a result which is 3 in this case.