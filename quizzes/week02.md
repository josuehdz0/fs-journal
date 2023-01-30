# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, const, and var(DONT USE)
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a subprogram designed to perform a particular task. They can be executed when they a are called (invoking a function).
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Had to google this
S - Single-responsibility Principle
O -  Open-closed Principle
L - Liskov Substitution
I - Interface Segregation Principle
D - Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Number 2, index counts start at 0
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
let time = 5
if(time<=12){
console.log('Good Morning');
  }else{
  console.log("I'm tired");
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
It is the third expression that tells us increment of the loop. i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. The HTML file. 
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
- Null
- Undefined
- Boolean
- Number
- BigInt
- String
- Symbol
- Object
- Function


```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
- Parameter are names created in the function definition and are seperated by commas in the () of a function. ex: function(parameter)
- Arguments are the values the function recieves from each parameter when the function is executed/invoked. 
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
- Primitive value is that isnt an object and has no methods. Like numbers, strings, and booleans. It has a single independent value. 

- Reference values are objects, arrays, and functions. It is a value that always points to something else. The reference points to where the actual data is stored. 