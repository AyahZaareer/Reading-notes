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

#### Functions in JavaScript are said to have lexical scope.  They are linked to the object they were defined within.  So, for each execution context, the scope is the  current execution context's variables object, plus the  variables object for each parent execution context.

## ERROR OBJECTS :

![image](https://user-images.githubusercontent.com/79833733/112393488-d1d8d980-8d03-11eb-92e3-d9eed5b3095b.png)


#### ERROR OBJECTS CONTINUED:

![image](https://user-images.githubusercontent.com/79833733/112393585-ffbe1e00-8d03-11eb-8698-a1a0b7cda9d8.png)

**hese two pages show JavaScript's seven different types of error objects  and some common examples of the kinds of errors you are likely to see. As you can tell, the errors shown by the browsers can be rather cryptic**


![image](https://user-images.githubusercontent.com/79833733/112393806-51ff3f00-8d04-11eb-8c23-c9dbd97d56bc.png)


### HOW TO DEAL WITH  ERRORS :

![image](https://user-images.githubusercontent.com/79833733/112393987-9ab6f800-8d04-11eb-9d4e-b7ebea9ad7b6.png)

### A DEBUGGING WORKFLOW:
**Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues.**

![image](https://user-images.githubusercontent.com/79833733/112394169-ed90af80-8d04-11eb-9a17-e0a5425651ac.png)




