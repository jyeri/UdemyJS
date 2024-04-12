### Udemy - JavaScript: Understanding the Weird Parts

- [x] S1: Getting started
- [x] S2: Execution Contexts and Lexical Environments
- [x] S3: Types and Operators
- [ ] S4: Objects and Operators
- [ ] S5: Object-Oriented Javascript and Prototypal Inheritance
- [ ] S6: Building Objects
- [ ] S7: Odds and Ends
- [ ] S8: Examining Famous Frameworks and Libraries
- [ ] S9: Let's build a Framework
- [ ] S10: EXTRA: TypeScript, ES6, and Transpiled Languages
- [ ] S11: EXTRA: Getting Ready for ECMAScript 6
- [ ] S12: EXTRA: ES6 in-depth
- [ ] S13: Conclusion


## In sights of sections

S1 - Basic information, how to set up your workspace and whats the point of this course

S2 - Basic functionality, key differences with other programming languages I have learned. General grasp of basics.

S3 -  Coercion, why '===' instead of the '==' most of the time.
Differences of C and JS in sense of types of variables (static and dynamic)

S4 - Objects, similarities to C structs when accessing with '.' operator.

Functions are objects, my C mind hurts.
So in JS functions can have properties, like in example (Function greet has given property of language via dot notation)!!!

Function statements and function expressions, how to utilize them.
-> function can be nameless

This object, what it is, how and why its created.
-> when created it points to global window object in browser
-> how to use self instead of this, so i know what to point all time
-> most of this is cleared with LET variable
--> so this points to global object (window this case), but when its method of an object its pointing to object. there is problem with internal tho

var Arr = []; is equal to var Arr = new Array();
-> dynamic so can hold anything (even function expressions and and objects, mixed) and no need to resizing like in C

JS had keyword for arguments, that contains all of the given argments
-> Unset arguments are allocated memoryspace and set to undefined
-> you can set default parameters (when not all arguments are given, use this)
--> name = name || "add first name";
-> console.log(arguments) to show what argument values passed, its Array-like.
--> that is stupid IMO
-> THIS IS MOSTLY DEPRICATED, USE SPREAD INSTEAD.
-> Spread = ...other


