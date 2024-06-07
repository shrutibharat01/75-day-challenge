# 🚀 Day 5/75 — Data Science Journey

Today, delved into Python functions, mastering their versatility and power. From understanding their foundations to exploring advanced techniques, we unlocked the secrets of efficient code organization and reusability. Stay tuned as we delve deeper into the realm of Python functions on our 75-day journey! 👩‍💻🔍✨

## Table of Contents
- [Argument Vs Parameter](#argument-vs-parameter)
- [*args Vs **kwargs](#args-vs-kwargs)
- [Memory execution](#memory-execution)
- [Namespaces (Variable scope)](#namespaces-variable-scope)
- [Nested functions](#nested-functions)
- [Decorators](#decorators)
- [Functions are 1st class citizen](#functions-are-1st-class-citizen)
- [Lambda functions](#lambda-functions)
- [Higher order functions](#higher-order-functions)
- [Coding Problems](#coding-problems)

## Argument Vs Parameter
Functions are reusable blocks of code that perform a specific task.

## *args Vs **kwargs
These special Python keywords are used to pass various arguments to a function.
- `*args`: Allows passing a variable number of non-keyword arguments to a function.
- `**kwargs`: Allows passing any number of keyword arguments. Internally, Python stores all values in a tuple for `*args` and in a dictionary for `**kwargs`.

## Memory Execution
Real-life example:
- Complete RAM: City
- Program scope/Global frame: House
- Function scope: 1 room in that house

## Namespaces (Variable scope)
Namespace is a system that ensures names are unique and can be used to avoid naming conflicts.
- **Built-in**: Contains all built-in functions and exceptions. Loaded automatically when Python starts up.
- **Global**: Contains names defined at the top level of the script or module. Remains active throughout the module.
- **Local**: Created for each function call. Contains names defined within that function. Destroyed once the function call is completed.
- **Enclosing Namespace (Non-local Namespace)**: Allows inner functions to access variables from the enclosing function’s scope.

## Nested functions
- **Simple Nested Function**: Inner function is defined inside outer function. Accessed only within the outer function.
- **Returning Nested Function**: Outer function returns inner function, accessible from external functions.
- **Passing Arguments to Nested Function**: Inner function accepts an argument, passed when calling the returned function.
- **Closure**: Inner function has access to variables from the enclosing scope of outer function.

## Decorators
Functions themselves that take another function as an argument and return a new function.
- Use cases: Logging, timing, authentication/authorization.

## Functions are 1st class citizen
Functions can be assigned to variables, passed as arguments, and returned from other functions.

## Lambda functions
- Defined using `lambda` keyword.
- Used for short, anonymous functions.

## Higher order functions
Functions that take another function as an argument or return a function as its result.
- **Map**
- **Filter**
- **Reduce**

## Coding Problems
- Python Program to Find LCM
- Python Program to Find HCF
- Python Program to Convert Decimal to Binary, Octal and Hexadecimal
- Python Program To Find ASCII value of a character
- Python Program to Make a Simple Calculator
- Python Program to Display Calendar

Thank you for reading! I’d love to hear your thoughts or questions about this blog on the Python functions. Feel free to join the conversation in the comments below!

Let’s continue the discussion on other platforms too. Connect with me on [LinkedIn](https://www.linkedin.com/in/shrutibharat01/) or [Github](https://github.com/shrutibharat01) for more data science insights and discussions. If you found this blog helpful, consider sharing it with your network!
