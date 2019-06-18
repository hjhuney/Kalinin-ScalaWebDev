# Scala Web Development

Notes and code from Denis Kalinin's ["Modern Web Development with Scala"](https://leanpub.com/modern-web-development-with-scala)

## Table of Contents

[Language Fundamentals]()
[Functional Programming]()


# Language Fundamentals

## Defining Values

3 main keywords

* val. Defines a constant (or value). 
* var. Defines a variable; very rarely used
* def. Defines a method

Scala has "type inference" so it can guess the type of a value. For example:

```
val num = 42

// output
num: Int = 42
```

We can define the data type explicitly. 

```
val num: Short = 42

//
num: Short = 42
```

When defining methods, it's required to specify argument types; specifying the return type is recommended but technically optional. 

```
def greet(name: String) = "Hello" + name

// output
greet: (name: String)String
```

specify return type:

```
def greet(name: String): String = "Hello " + name
```

If you want to create a method that doesn't return anything, you can use Unit:

```
def greet(): Unit = println("Hello!")
```

## Parameterless Method

You can also define method without parenthesis: 

```
def randomNum = Math.random
```

This is a parameterless method. 

## Functional Types




# Functional Programming
