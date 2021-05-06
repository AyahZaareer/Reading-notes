# What is a ‘call’?
### The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous. The understanding of the call stack is vital to Asynchronous programming.a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

# How many ‘calls’ can happen at once?
### 

# What does LIFO mean?
### LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

# Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![image](https://user-images.githubusercontent.com/79833733/117363708-9cf4a080-aec5-11eb-84f4-66b804c8bdde.png)
### This is what happens when the code is run:

**1. When secondFunction() gets executed, an empty stack frame is created. It is the main (anonymous) entry point of the program.**

**2. secondFunction() then calls firstFunction()which is pushed into the stack.**

**3. firstFunction() returns and prints “Hello from firstFunction” to the console.**

**4. firstFunction() is pop off the stack.**

**5. The execution order then move to secondFunction().**

**6. secondFunction() returns and print “The end from secondFunction” to the console.**

**7. secondFunction() is pop off the stack, clearing the memory.**

# What causes a Stack Overflow?
### A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

![image](https://user-images.githubusercontent.com/79833733/117364173-4045b580-aec6-11eb-8b90-22466cbf6155.png)
### The callMyself() will run until the browser throws a “Maximum call size exceeded”. And that is a stack overflow.



