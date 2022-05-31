# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The three pillars of object oriented programming are- encapsulation, inheritance, and polymorphism.
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
encapsulation is the idea that you group together data and methods in the same areas. These areas are also limited in their access outside as well as others are limited in their reach inside.

```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S stands for single responsibility. Each function should do one specific thing.

```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a definition of what an instance should look like. A class is like a blueprint and an instance is like a house. A class technically doesn't exist yet and it can't be used in the same way that an instance can be.

```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is an instance of another object with some rules attached to it. It can have traps which limit the actions that can be taken on the proxy object. It can also monitor to see if actions are taken on the proxy and can be programmed to take actions accordingly. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of the MVC pattern is to increase code organization as well as encapsulate functions and data. This is especially useful as applications become larger and if you want to hide certain things from users.

```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is responsible for interacting with the document. The controller doesn't manipulate data. It is purely a middle man between the service and the document and is the only thing that can interact with the document directly.

```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is responsible for manipulating data. It will be the one doing the computing work and relaying that information back to the controller. The service has no contact with the document. 

```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is used to model data. This is where your datatype classes reside and what is called every time you create data. Classes are stored in the model and they are used to create specific datatypes that will be manipulated and displayed using the service and controller.
```
