# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```

The entrypoint to an application is the index.html file. The entry point to the index.html is the main.js file. 

```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```

components are reusable segments that will be displayed on a page. You will dynamically inject components into pages. Many components may also be present on many pages such as certain buttons, or account information displays.

```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```

the v-for feature of vue allows you to repeat a section of html while passing through data for each iteration.

```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
template, script, and style

```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```

Liskov substitution principle 

```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```

vue uses the router-link component

```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```

The state object within a component will rerender when the data changes. It has to be specified/ grabbed from the Appstate. components will not re-render when data in the appstate changes.

```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```

The services are responsible for manipulating data within the appstate and to make calls to apis.

```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The main.js file is the file that contains the root element of the vue project.


```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```

the #app tag is used to alter the styling of the entire vue project. Adding the scoped attribute to this tag will limit it to just the component it exists.

```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```

watchEffect is the method that creates watchable objects.

```