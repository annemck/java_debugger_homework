1. What is the purpose of a breakpoint?
A breakpoint pauses the debugger when that line of code is just about to be run to allow that section to be checked in more depth. You can also place multiple breakpoints to pause regularly and check several parts of the code or just place it on a method to pause the debugger whenever that method is run.

2. Does the line of code on a breakpoint run when you start debugging?
No. It pauses on the line but doesn't start executing it.

3. How do we debug the next line of code?
We can use 'step over' to run the current line of code we're paused on and pause at the start of the next line of code instead.

4. What does the step into command do?
It steps into the method that is being called on that line. It will take you to the file and line where that method is stored and pause just before it starts running so it can be checked in more depth.

5. What is the difference between evaluate expression and evaluate code fragment?
Evaluate expression can write java code and run methods on instances that have been called so far while running the debugger. Whereas evaluate code fragment basically allows you to write normal java and call any methods from any class within the folder you're working in, not just the ones that have been called so far.
