#                                                       Debugging


 ## Error Handling & Debugging
 
 **ORDER OF EXECUTION**
 To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:
![debug](https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg)

**EXECUTION CONTEXTS**
* EXECUTION CONTEXTS
* EVAL CONTEXT
* FUNCTION CONTEXT
* GLOBAL SCOPE
* FUNCTION-LEVEL SCOPE

**EXECUTION CONTEXT & HOISTING**
Each time a script enters a new execution context, there are two phases of activity:
1. Prepare
  * The new scope is created
  * Variables, functions, and arguments are created
  * The value of the this keyword is determined
2. Execute
  * Now it can assign values to variables
  * Reference functions and run their code
  * Execute statements
  
>If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

>Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

These two pages show JavaScript's seven different types of error objects:
1.TypeError
2.RangeError

**Setting Breakpoints**
In the debugger window, you can set breakpoints in the JavaScript code.

At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.

After examining values, you can resume the execution of code (typically with a play button).

* The `debugger` keyword stops the execution of JavaScript, and calls (if available) the debugging function. This has the same function as setting a breakpoint in the debugger. If no debugging is available, the debugger statement has no effect.

Major Browsers' Debugging Tools:

* Chrome
1.Open the browser.
2.From the menu, select "More tools".
3.From tools, choose "Developer tools".
4.Finally, select Console.

* Firefox
1.Open the browser.
2.From the menu, select "Web Developer".
3.Finally, select "Web Console".

##### source: [Duckett JS book](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1119038634.html)
