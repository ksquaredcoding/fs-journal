# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
encapsulation, inheritance, and polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Separating different parts of code in different sections to be accessed level by level to achieve the end goal
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single-responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class contains all the information that may need to be accessed in creation, page load, etc. An instance is just using that info, like a car class would be everything a car needs, but an instance of a car would be a bmw built from that info.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy is a stand in version that allows the original to remain untouched but still allow access and use of its data.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To separate the jobs into different parts. It keeps load times lower, creates more developer control, and only gives users access to the things they need.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
To allow them to interact with things on the page and direct the requests to services or other controllers.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service updates the data and does any actual logic to change the appstate.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is what items and things are built off of, and show how things will be built out for the user.
```
