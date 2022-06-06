# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```

Asynchronous code allows certain functions to run, in conjunction with others. This means that you can use the output of one function as the input of another function. 

```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```

An event listner will watch for certain events, or data changes to occur and then will conduct a specific action. We use them commonly in our projects for draw functions.

```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```

The O in the solid principles stands for the open closed principle. This means that objects should be open for extensions but closed for modifications. You can add data, but cannot take away already established data.

```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```

A callback or a higher order function is a function passed as an argument in another function. This allows for asynchronous code but can also get really complicated and convoluted very quickly. 

```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```

A promise is just that. A promise to return a certain value at some point in the future. You capture an error from a promise using the catch method. This allows you to specify what you want done if a promise fails to deliver a value.

```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```

Three processes used to make requests over HTTP include Get, Post, and Put. Get will receive data from an API, Post will add data to an API, and Put will edit data in an API.

```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```

API stands for application programming interface.

```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```

In the MVC pattern, the service is responsible for making calls to APIs.

```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```

Encapsulation is used to increase organization and readability in programs. It groups data and functions that hold similar responsibilities in the same scope of the program. This makes it less likely that you will interact with the wrong data when creating functions and make your code much more readable.

```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```

20 is a broad code for a successful request. There are other successful request codes such as 201, 202, 203, and 204 among others. 

```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```

a 500 error is an error that indicates that the server has ran into an issue. It is a broad error that simply states that the server ran into a problem.

```