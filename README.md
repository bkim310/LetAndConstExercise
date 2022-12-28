# LetAndConstExercise
var PI = 3.14;
PI = 42; // stop me from doing this!

const PI = 3.14;
PI = 42; //not allowed to reassign nor redeclare a const variable

What is the difference between var and let?
Let is in the block scope and cannot be redeclared while var is in the function scope and can be redeclared as well as reassigned.

What is the difference between var and const?
Const is in the block scope and cannot be reassigned nor redeclared while vaar can. 

What is the difference between let and const?
They are both in the block scope but const cannot be reassigned while let can be. 

What is hoisting?
Hoisting is when var variables can be called in functions/methods before the var is intialized because the browser will read all of the var variables that are defined before reading the rest of the code. 
