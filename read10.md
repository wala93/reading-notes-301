
# THE CALL STACK
 THE CALL STACK: its away that  to keep track  that calls multiple functions — what function is
 currently being run and what functions are called from within that function, etc.
 
 this is how the function excute in stack :
 When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

## so, 
**the call stack is synchronous.**

What causes a stack overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## Types of error messages

The first thing that indicates you that something is wrong with your code is the (in)famous
error message that the one we saw just moments ago, it usually appears on your console .


##so type of errors like :
Reference errors
Syntax errors
Range errors
Type errors
