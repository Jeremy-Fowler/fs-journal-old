# What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

A function declaration defines a named function:
function name(parameters) {}
It is hoisted so it can be used before it is defined.

A Function Expression can define an unnamed function:
let name = function(parameters) {}
It is not hoisted.

An arrow function is a shorter version of writng a function:
let name = (parameters) => {}
It does not creat a "this" value

## What is the difference between Parameters and Arguments?

Parameters are used when defining a function, arguments are used while invoking the function.

## What are higher order functions? Can you provide an example?

A higher order function either accepts another function as a perameter, or returns a function.
Array.prototype.map is a higher order function that I have used before.

https://jeremy-fowler.github.io/js-intro-loops-arrays/