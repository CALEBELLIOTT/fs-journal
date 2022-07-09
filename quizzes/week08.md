# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```

package.json is a file that contains metadata for a project that is utilized by NPM. This includes what dependencies that project has, what packages it utilizes, and more. 

``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```

You need your package.json in the root of your application. 

```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```

npm run build

```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```

.env files

```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```

Heroku CLI or the heroku dashboard.

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```

clone your github repository, make your changes, push to github, push to heroku master branch. 

```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```

Branching is important as it allows developers to work on certain parts of a project and "merge" them with other parts. This can help eliminate risk of destroying working pieces of code while developing new code. 

```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```

Code review should happen before code is merged with the main branch. 

```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```

Merging is the term used to define combining two branches.

```