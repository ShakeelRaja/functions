# Functions and Scope

## SWABT
* Understand the use case for functions in programming (abstraction and reuse)
* Create and use functions in Python

## Functions 

A function is a block of organized, reusable code that is used to perform a single, related action. Functions provide better modularity for your application and a high degree of code reusing.

As you have already seen, Python gives you many built-in functions like print(), etc. but you can also create your own functions. These functions are called user-defined functions.

## Defining a Function

You can define functions to provide the required functionality. Here are simple rules to define a function in Python.

* Function blocks begin with the keyword `def` followed by the function name and parentheses ( ( ) ).

* Any input parameters or arguments should be placed within these parentheses. You can also define parameters inside these parentheses.

* The first statement of a function can be an optional statement - the documentation string of the function or docstring.

* The code block within every function starts with a colon (:) and is indented.

* The statement `return [some expression]` exits a function, optionally passing back an expression to the caller. A return statement with no arguments is written as `return None`.

## Syntax of a Function

A common syntax of a function in python may look like this:

```

def functionname( parameter1, parameter2 .. ):
   "function_docstring"
   function_processing
   return [expression]
```
By default, parameters have a positional behavior and you need to inform them in the same order that they were defined. e.g., look at the this function which takes in a string as input parameter and prints in on screen.
```
def printString( str ):
   "This prints a passed string into this function"
   print str
   return
```
### Calling a Function

Once the basic structure of a function is finalized, you can execute it by calling it from another function or directly from the Python prompt. Following is the example to call printString() function
```
#!/usr/bin/python

# Function definition is here
def printString( str ):
   "This prints a passed string into this function"
   print str
   return

# Call printme function with some string as input argument
printme("Calling the user defined function!")
printme("Second call to the same function")
```

Above code will print 
```
Calling the user defined function!
Second call to the same function
```
