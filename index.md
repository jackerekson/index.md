1. Don't use ' == '

In JavaScript there are both '== ' and '===' and you might be used to "==" in other programming languages and might continue using the same, But using it without knowing how it works might bring few bugs which might be difficult to track. Read my previous article to know more.

2. Use "let" over "var"

When declaring variables you might have come across 'var' and 'let' but "var" is not recommended as it brings some problems along with it. It will be easier to understand with an example.

3. Use Immutable variables or "const"

Use 'const' to declare variables as much as you can Unless the data changes in the variable like the 'i' inside the for-loop. Here are few examples

https://blog.hrithwik.me/10-best-javascript-practices-recommended-by-top-developers


4. KEEP IT SHORT, STUPID!

You have read this a zillion times already. As a programmer/webmaster you might have applied this tip multiple times too but never forget this in case of JavaScript.
Use comments and white spaces while in development mode to keep your code readable.
Remove white spaces and comments before publishing your scripts in live environment. Also, try to shorten your variable and function names.
Consider using third party tools to compress your JavaScript code before publishing the same

5. THINK BEFORE YOU TOUCH OBJECT PROTOTYPES

Appending new properties to object prototypes is one of the most common reasons for script failures.

6. DEBUG JAVASCRIPT CODE

Even the best programmers make mistakes. To limit them, run your JavaScript code through a JavaScript debugger to make sure that you haven’t made any silly blunders that can easily be prevented.

7. NEVER USE “VAR” MULTIPLE TIMES

While initializing every variable programmers tend to use “var” keyword. Instead, it is suggested that you use commas to avoid redundancy of keywords and reduce code size:
var variableOne = ‘string 1’,
variableTwo = ‘string 2’,
variableThree = ‘string 3’;

https://www.developerdrive.com/top-10-must-follow-javascript-best-practices-2/

8. Declare and initialize your variables at the top
Nothing disrupts readability like a late declaration. Just as it’s easier to take out all your tools before starting a job, it’s simpler to declare all variables before getting into the nitty-gritty of your function. This gives easy access should we need to tweak any name or value later down the line.

While on the topic of variables, it’s best practice to initialize your variables at the time of creation so you and your team can ensure none are left undefined.

9. Declare and initialize your variables at the top
Nothing disrupts readability like a late declaration. Just as it’s easier to take out all your tools before starting a job, it’s simpler to declare all variables before getting into the nitty-gritty of your function. This gives easy access should we need to tweak any name or value later down the line.

While on the topic of variables, it’s best practice to initialize your variables at the time of creation so you and your team can ensure none are left undefined.

10. Be efficient with DOM manipulations
Accessing the DOM is essential for getting the most out of your program, but doing so repeatedly causes visual clutter and will slow down the program.

Instead, access it once and cache it for later use in a variable. From then on, you can access that variable instead of the DOM directly. This process is visually cleaner and more efficient.

https://www.educative.io/blog/javascript-tips-simplify-code
