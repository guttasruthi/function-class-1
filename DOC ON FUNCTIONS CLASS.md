FUNCTIONS:
A function is a block of code which only runs when it is called.
you can pass the data as parameters, into a funtion.
A function can return data as a result.

Defining a function:

Syntax:

def function_name(arguments):
    block of code

Description of syntax:


Def is a keyword which defining a function.

function_name is a name we give to the function.

parameters considered as variables that we use inside the function.


```python
def my_function():
    print("Hello from a function")
my_function()
```

    Hello from a function
    

Calling a function:

To call a function,use the function name followed by paranthesis():

Syntax:

Function_name(arguments)

Arguments are actual inputs for function.
    


```python
def my_function():
  print("Hello from a function")

my_function()
```

    Hello from a function
    

You can pass the arguments in two ways:
1. Postional Arguments:

    * positional arguments are the most common way to pass arguments to a function.
    * They are matched to the functions parameters in the order they are passed.
    * The function definition specifies the parameters and when you call the function ,you provide values in the same order.



```python
def add_numbers(x, y):
    a = x + y
    return(a)
# calling the funtion with positional arguments
a = add_numbers(3,5)
print("the sum is:",a)

```

    the sum is: 8
    

Positional arguments are useful when the order of the arguments matters, and it's essential to provide the correct values in the expected order to get the desired behavior from the function.


2. Keyword Arguments:

    * keyword arguments allow you to specify the parameter values by naming the parameters when calling a function.
    * This can make your code more readable and allow you to provide arguments in a different order than they are defined in the function.


```python
def my_function(child3, child2, child1):
    print("The youngest child is " + child3)

my_function(child1 = "Emil", child2 = "Tobias", child3 = "Linus")
```

    The youngest child is Linus
    

Default Parameters:

* Default arguments allow you to provide a default value for a function parameter if the caller of the function does not provide a value for that parameter.

* To define a default argument in a function, you assign a default value to the parameter in the function's definition.


Syntax for defining a funtion in default arguments:

def function_name(parameter1=default_value1, parameter2=default_value2, ...):
    # Function code


```python
def greet(name, greeting="Hello"):
    print(f"{greeting}, {name}!")

# Call the function with both parameters provided
greet("Alice", "Hi") 


# Call the function with only the 'name' parameter provided
greet("Bob")
```

    Hi, Alice!
    Hello, Bob!
    

Doc Strings:
    
   * a docstring is a string literal that is used as a comment to document a specific module, class, method, or function.       
   * Docstrings are placed within triple-quoted strings (either single or double quotes) and are typically used to provide     information about the purpose, usage, and behavior of the module, class, or function.
   * They serve as a form of documentation to help programmers understand how to use the code.


```python

```


```python

```
