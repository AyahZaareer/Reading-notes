## How to Solve Programming Problems:
  1.Read the problem completely twice.

  2.Solve the problem manually with 3 sets of sample data.

  3.Optimize the manual steps.

  4.Write the manual steps as comments or pseudo-code.

  5.Replace the comments or pseudo-code with real code.

  6.Optimize the real code.

## How to think like a programmer?
### The best way involves:

a) having a framework 

b) practicing it.

### Have a framework:
#### 1. Understand:
#### Know exactly what is being asked. Most hard problems are hard because you don’t understand them (hence why this is the first step).How to know when you understand a problem? When you can explain it in plain English.

#### 2. Plan:
#### Don’t dive right into solving without a plan (and somehow hope you can muddle your way through). Plan your solution! Nothing can help you if you can’t write down the exact steps.In programming, this means don’t start hacking straight away. Give your brain time to analyze the problem and process the information.

#### 3. Divide:
#### Pay attention. This is the most important step of all.Do not try to solve one big problem. You will cry.Instead, break it into sub-problems. These sub-problems are much easier to solve.Then, solve each sub-problem one by one. Begin with the simplest. Simplest means you know the answer (or are closer to that answer).After that, simplest means this sub-problem being solved doesn’t depend on others being solved.

#### 4. Stuck?
#### By now, you’re probably sitting there thinking “Hey Richard... That’s cool and all, but what if I’m stuck and can’t even solve a sub-problem??” First off, take a deep breath. Second, that’s fair. Don’t worry though, friend. This happens to everyone! The difference is the best programmers/problem-solvers are more curious about bugs/errors than irritated.


### In fact, here are three things to try when facing a whammy:
#### Debug: Go step by step through your solution trying to find where you went wrong. Programmers call this debugging (in fact, this is all a debugger does).

#### Reassess: Take a step back. Look at the problem from another perspective. Is there anything that can be abstracted to a more general approach?

#### Research: Ahh, good ol’ Google. You read that right. No matter what problem you have, someone has probably solved it. Find that person/ solution. In fact, do this even if you solved the problem! (You can learn a lot from other people’s solutions).

### Practice:
#### Don’t expect to be great after just one week. If you want to be a good problem-solver, solve a lot of problems! Practice. Practice. Practice. It’ll only be a matter of time before you recognize that “this problem could easily be solved with < insert concept here>.”

## 5 Whys Getting to the Root of a Problem Quickly:
#### The 5 Whys uses "counter-measures," rather than "solutions." A counter-measure is an action or set of actions that seeks to prevent the problem from arising again, while a solution may just seek to deal with the symptom. As such, counter-measures are more robust, and will more likely prevent the problem from recurring.

### How to Use the 5 Whys:
#### 1. Assemble a Team:
#### Gather together people who are familiar with the specifics of the problem, and with the process that you're trying to fix. Include someone to act as a facilitator , who can keep the team focused on identifying effective counter-measures.

#### 2. Define the Problem.
##### If you can, observe the problem in action. Discuss it with your team and write a brief, clear problem statement that you all agree on.

#### 3. Ask the First "Why?"
##### Asking "Why?" sounds simple, but answering it requires serious thought. Search for answers that are grounded in fact: they must be accounts of things that have actually happened, not guesses at what might have happened.

#### 4. Ask "Why?" Four More Times.

![image](https://user-images.githubusercontent.com/79833733/123252812-5bf83000-d4f5-11eb-9f55-62cffa01ded4.png)


![image](https://user-images.githubusercontent.com/79833733/123252890-729e8700-d4f5-11eb-9d96-885dec9536fe.png)



#### 5. Know When to Stop.
##### You'll know that you've revealed the root cause of the problem when asking "why" produces no more useful responses, and you can go no further. An appropriate counter-measure or process change should then become evident.

#### 6. Address the Root Cause(s).
##### Now that you've identified at least one root cause, you need to discuss and agree on the counter-measures that will prevent the problem from recurring.
#### 7. Monitor Your Measures.
##### Keep a close watch on how effectively your counter-measures eliminate or minimize the initial problem. You may need to amend them, or replace them entirely. If this happens, it's a good idea to repeat the 5 Whys process to ensure that you've identified the correct root cause.

## What is JavaScript?
### JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which (HTML and CSS) we have covered in much more detail in other parts of the Learning Area.

![image](https://user-images.githubusercontent.com/79833733/122967474-29362680-d393-11eb-8293-46b229ff0d1b.png)

**- HTML:** is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page.

**-CSS :** is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.

**-JavaScript:** is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)

## V8 Runtime Overview:
### V8 is the name of the JavaScript engine that powers Google Chrome. It's the thing that takes our JavaScript and executes it while browsing with Chrome. V8 provides the runtime environment in which JavaScript executes. The DOM, and the other Web Platform APIs are provided by the browser.V8 provides the runtime environment in which JavaScript executes. The DOM, and the other Web Platform APIs are provided by the browser.

### V8 is written in C++, and it's continuously improved. It is portable and runs on Mac, Windows, Linux and several other systems.

## Call stack:
### A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

.When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.

.Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.

.When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.

.If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

![image](https://user-images.githubusercontent.com/79833733/122968425-36074a00-d394-11eb-814f-10dc1c541fbe.png)

#### The code above would be executed like this:

1-Ignore all functions, until it reaches the greeting() function invocation.

2-Add the greeting() function to the call stack list

![image](https://user-images.githubusercontent.com/79833733/122968718-84b4e400-d394-11eb-9930-6d6407c98926.png)


3-Execute all lines of code inside the greeting() function.

4-Get to the sayHi() function invocation.

5-Add the sayHi() function to the call stack list.

![image](https://user-images.githubusercontent.com/79833733/122968868-aada8400-d394-11eb-887e-8c67c530f878.png)

6-Execute all lines of code inside the sayHi() function, until reaches its end.

7-Return execution to the line that invoked sayHi() and continue executing the rest of the greeting() function.

8-Delete the sayHi() function from our call stack list

![image](https://user-images.githubusercontent.com/79833733/122968976-cba2d980-d394-11eb-9e16-06e4e0b725c2.png)

9-When everything inside the greeting() function has been executed, return to its invoking line to continue executing the rest of the JS code.

10-Delete the greeting() function from the call stack list.

![image](https://user-images.githubusercontent.com/79833733/122969059-e70de480-d394-11eb-9138-87c8c405c9de.png)

**In summary, then, we start with an empty Call Stack. Whenever we invoke a function, it is automatically added to the Call Stack. Once the function has executed all of its code, it is automatically removed from the Call Stack. Ultimately, the Stack is empty again.**


## Asynchronous callbacks :
### Functions that are specified as arguments when calling a function which will start executing code in the background. When the background code finishes running, it calls the callback function to let you know the work is done, or to let you know that something of interest has happened.



