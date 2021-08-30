# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a block of code that runs when it is invoked
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S — Single responsibility principle
O — Open closed principle
L — Liskov substitution principle
I — Interface segregation principle
D — Dependency Inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
pineappple is at the 2 index.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
them.push(you.friends)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
A conditional can be an else; if statement

if (conditional == true){
  return true
}else return false
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
The incrementor belongs in the empty space in the for loop. If you wanted to increase the value of i on every iteration, you would type i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model. the index.html is first accessed to render the DOM.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
  number
  string
  boolean
  undefined
  null
  symbol
    objects
    arrays
    functions

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are used when defining a function, arguments are used while invoking the function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive Values
  number
  string
  boolean
  undefined
  null
  symbol

Reference Values
  anything that is "typeof" "object"
    objects
    arrays
    functions

```