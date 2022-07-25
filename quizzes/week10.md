# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```

The purpose of a namespace is to seperate code into different scopes based on the purpose/ context of that code. For example, controllers, services, models, and respositories all have different namespaces. 
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```

A struct is very similar to a class except instead of a reference type it is a value type. This means that it doesn't store pointers to the data, it stores the value of the data directly.

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```

The method that returns an instance of a class is the "new" method. This will instantiate the class.

```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```

The access modifier is "public". This means that there is not a limit to where the method can be scoped.

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```

String is the return type of the method. 

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```

Abstract is a keyword that allows you to create a class that is incomplete and must be implemented in a derived class. In other words, the abstract keyword prevents you from instantiating the class without adding it to another class. 

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```

Virtual means that the method is available to use on the class definition rather than the instantiated version of the class. 

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```

public, private, internal, protected.

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```

The code within that class or method will only be available within that class. 

```