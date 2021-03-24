# HANDLING ERRORS :
## ORDER OF EXECUTION :
#### To find the source of an error, it helps to know how scripts are processed.  The order in which statements are executed can be complex; some tasks  cannot complete until another statement or function has been run: 

![image](https://user-images.githubusercontent.com/79833733/112392480-224f3780-8d02-11eb-9cd8-ffa5a3fb34c0.png)



## EXECUTION CONTEXTS :
#### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new  new execution context. They correspond to variable scope. 


![image](https://user-images.githubusercontent.com/79833733/112392624-680c0000-8d02-11eb-9384-54db5d603ae8.png)


## EXECUTION CONTEXT & HOISTING:

**Each time a script enters a new execution context, there are two phases  of activity:**

![image](https://user-images.githubusercontent.com/79833733/112393030-11eb8c80-8d03-11eb-9d64-5b8b5f5a0a53.png)

## UNDERSTANDING SCOPE:
#### In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object. 

#### Functions in JavaScript are said to have lexical scope.  They are linked to the object they were defined within.  So, for each execution context, the scope is the  current execution context's variables object, plus the  variables object for each parent execution context
