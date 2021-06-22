## How to Solve Programming Problems:
1.Read the problem completely twice.

2.Solve the problem manually with 3 sets of sample data.

3.Optimize the manual steps.

4.Write the manual steps as comments or pseudo-code.

5.Replace the comments or pseudo-code with real code.

6.Optimize the real code.

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

