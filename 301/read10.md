### Understanding the JavaScript Call Stack
- What is a ‘call’?
The call stack is primarily used for function invocation (call). 

- How many ‘calls’ can happen at once?
Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

- What does LIFO mean?
 Last In, First Out 
- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

- What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. 


### JavaScript error messages
- What is a ‘refrence error’?
when you try to use a variable that is not yet declared you get this type os errors.
- What is a ‘syntax error’?
this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

- What is a ‘range error’?
when you Try to manipulate an object with some kind of length and give it an invalid length 
- What is a ‘tyep error’?
this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

- What is a breakpoint?
which will make your program stop at that point only if a condition is met
- What does the word ‘debugger’ do in your code?
The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.
## Things I want to know more about