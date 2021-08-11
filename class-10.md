# Error Handling & Debugging
Execution command: To find the source of the error, it is useful to know how scripts are handled. The order in which the statements are executed can be complex.

## EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity:
1. PREPARE 
* The new scope is created 
* Variables, functions, and arguments are created 
* The value of the this keyword is determined 
2. EXECUTE 
* Now it can assign values to variables 
* Reference functions and run their code 
* Execute statements 
## UNDERSTANDING ERRORS
If the JavaScript statement causes an error, it throws an exception. At this point, the compiler stops and looks for exception-handling code.
## ERROR OBJECTS
Error objects can help you find where your mistakes are and browsers have tools to help you read them.

## DEAL WITH  ERRORS
Now that you know what the error is and how the browser deals with it, there are a couple of things you can do with the errors.
1: Decompile the script to fix errors: If you encounter an error while writing a script (or when someone reports a bug), you will need to debug the code and track down the source of the error and fix it.
2: Handle errors gracefully Handle errors gracefully using try , catch , throw , and f i na 1 ly statements .
## A DEBUGGING WORKFLOW
DEBUGGING is the deduction: getting rid of the possible causes of the error. Here is a workflow of the techniques you'll meet over the next 20 pages. Try to narrow down the problem, then look for clues.

If you understand execution contexts (which have two phases) and stacks, you are more likely to find the error in your code. Correction is the process of finding errors. It involves a discount process. The console helps narrow down the area where the error is, so that you can try to find the exact error. JavaScript contains 7 different types of errors. Each creates its own error object, which can tell you its line number and provide a description of the error. If you know you might get an error, you can safely handle it with try, catch, and finally statements. Use it to provide users with helpful feedback.
