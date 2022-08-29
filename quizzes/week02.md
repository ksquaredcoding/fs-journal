# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A section of logic that is performed when called
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S- Single-Responsibility Principle
O- Open-Closed Principle
L- Liskov Substitution Principle
I- Interface Segregation Principle
D- Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
index = 2, you start at 0 when looking at index position in an array
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you[friends].push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(x < 0)
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, HTML or index.html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
1. Primitive Values
2. Boolean
3. Null
4. Undefined
5. Number
6. BigInt
7. String
8. Symbol
9. Objects
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is the variables you set the function up to take in and when defining a function. Arguments are the values received from each parameter when the function is executed or invoked.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A Primitive is set as this is the single value of what you are defining: let x = 7

A Reference is one where there are multiple values contained with in an object (or an array which is just a type of object) const myArr = [3, 7]
```