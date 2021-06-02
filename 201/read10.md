### Error Handling & Debugging

" 
** Each time a script enters a new execution context, there are two phases ** 
of activity: 
1: PREPARE 
- The new scope is created .
- Variables, functions, and arguments are created .
- The value of the this keyword is determined.
2: EXECUTE 
- Now it can assign values to variables. 
- Reference functions and run their code.
- Execute statements. "[1]

### How to deal with errors
- Debug the script to fix errors, it involves a 
process of deduction. .
- Handle errors gracefully using the try, catch, finally statements.
- The console helps narrow down the area in which the 
error is located, so you can try to find the exact error.

"
**JavaScript has 7 different types of errors. Each creates 
its own error object, which can tell you its line number 
and gives a description of the error.**" [2]

resource: 
From the Duckett JS book 
[1] p.456
[2] p.486