### Intro to Debugging in IDE

#### Questions:
1. What is the purpose of a breakpoint?
2. Does the line of code on a breakpoint run when you start debugging?
3. How do we debug the next line of code?
4. What does the step into command do?
5. What is the difference between evaluate expression and evaluate code fragment?

#### Answers:
1. When a breakpoint is inserted into code, it will stop running at that point and launch the debugger console.
2. No, it is not run until it is stepped through.
3. We can either use "step over" to go immediately to the next line or we can use "step into" to go through any function that is called.
4. Step into is used to also step through any methods or functions that are called in the code.
5. Evaluate expression allows you to write a single line of code accessing the debugger data. Evaluate code fragment allows you to do the same with multiple lines of code.