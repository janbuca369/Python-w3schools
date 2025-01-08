## Variables

Variables are containers for storing data values.

---

## Creating Variables

Python has no command for declaring a variable.

A variable is created the moment you first assign a value to it.

### Example[Get your own Python Server](https://www.w3schools.com/python/python_server.asp "W3Schools Spaces")

x = 5  
y = "John"  
print(x)  
print(y)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables1)

Variables do not need to be declared with any particular _type_, and can even change type after they have been set.

### Example

x = 4       # x is of type int  
x = "Sally" # x is now of type str  
print(x)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables2)

---

## Casting

If you want to specify the data type of a variable, this can be done with casting.

### Example

x = str(3)    # x will be '3'  
y = int(3)    # y will be 3  
z = float(3)  # z will be 3.0

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_casting)

---

---

## Get the Type

You can get the data type of a variable with the `type()` function.

### Example

x = 5  
y = "John"  
print(type(x))  
print(type(y))

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_type)

You will learn more about [data types](https://www.w3schools.com/python/python_datatypes.asp) and [casting](https://www.w3schools.com/python/python_casting.asp) later in this tutorial.

---

## Single or Double Quotes?

String variables can be declared either by using single or double quotes:

### Example

x = "John"  
# is the same as  
x = 'John'

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables7)

---

## Case-Sensitive

Variable names are case-sensitive.

### Example

This will create two variables:

a = 4  
A = "Sally"  
#A will not overwrite a

# Python - Variable Names

---

## Variable Names

A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:

- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)
- A variable name cannot be any of the [Python keywords](https://www.w3schools.com/python/python_ref_keywords.asp).

### Example[Get your own Python Server](https://www.w3schools.com/python/python_server.asp "W3Schools Spaces")

Legal variable names:

myvar = "John"  
my_var = "John"  
_my_var = "John"  
myVar = "John"  
MYVAR = "John"  
myvar2 = "John"

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variable_names_legal)

### Example

Illegal variable names:

2myvar = "John"  
my-var = "John"  
my var = "John"

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variable_names_error)

Remember that variable names are case-sensitive

---

---

## Multi Words Variable Names

Variable names with more than one word can be difficult to read.

There are several techniques you can use to make them more readable:

## Camel Case

Each word, except the first, starts with a capital letter:

myVariableName = "John"

---

## Pascal Case

Each word starts with a capital letter:

MyVariableName = "John"

---

## Snake Case

Each word is separated by an underscore character:

my_variable_name = "John"

---

# Python Variables - Assign Multiple Values

[❮ Previous](https://www.w3schools.com/python/python_variables_names.asp)[Next ❯](https://www.w3schools.com/python/python_variables_output.asp)

---

## Many Values to Multiple Variables

Python allows you to assign values to multiple variables in one line:

### Example[Get your own Python Server](https://www.w3schools.com/python/python_server.asp "W3Schools Spaces")

x, y, z = "Orange", "Banana", "Cherry"  
print(x)  
print(y)  
print(z)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables8)

**Note:** Make sure the number of variables matches the number of values, or else you will get an error.

---

## One Value to Multiple Variables

And you can assign the _same_ value to multiple variables in one line:

### Example

x = y = z = "Orange"  
print(x)  
print(y)  
print(z)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables6)

---

## Unpack a Collection

If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables. This is called _unpacking_.

### Example

Unpack a list:

fruits = ["apple", "banana", "cherry"]  
x, y, z = fruits  
print(x)  
print(y)  
print(z)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_unpack)

Learn more about unpacking in our [Unpack Tuples](https://www.w3schools.com/python/python_tuples_unpack.asp) Chapter.

---

# Python - Output Variables

---

## Output Variables

The Python `print()` function is often used to output variables.

### Example[Get your own Python Server](https://www.w3schools.com/python/python_server.asp "W3Schools Spaces")

x = "Python is awesome"  
print(x)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_print)

In the `print()` function, you output multiple variables, separated by a comma:

### Example

x = "Python"  
y = "is"  
z = "awesome"  
print(x, y, z)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables3)

You can also use the `+` operator to output multiple variables:

### Example

x = "Python "  
y = "is "  
z = "awesome"  
print(x + y + z)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables4)

Notice the space character after `"Python "` and `"is "`, without them the result would be "Pythonisawesome".

For numbers, the `+` character works as a mathematical operator:

### Example

x = 5  
y = 10  
print(x + y)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables5)

In the `print()` function, when you try to combine a string and a number with the `+` operator, Python will give you an error:

### Example

x = 5  
y = "John"  
print(x + y)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_test)

The best way to output multiple variables in the `print()` function is to separate them with commas, which even support different data types:

### Example

x = 5  
y = "John"  
print(x, y)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_comma)

---

## Exercise?

Consider the following code:  
`print('Hello', 'World')`  
What will be the printed result?

  

Hello, World

Hello World

HelloWorld

  
Submit Answer »


# Python - Global Variables

[❮ Previous](https://www.w3schools.com/python/python_variables_output.asp)[Next ❯](https://www.w3schools.com/python/python_variables_exercises.asp)

---

## Global Variables

Variables that are created outside of a function (as in all of the examples in the previous pages) are known as global variables.

Global variables can be used by everyone, both inside of functions and outside.

### Example[Get your own Python Server](https://www.w3schools.com/python/python_server.asp "W3Schools Spaces")

Create a variable outside of a function, and use it inside the function

x = "awesome"  
  
def myfunc():  
  print("Python is " + x)  
  
myfunc()

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_global)

If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function. The global variable with the same name will remain as it was, global and with the original value.

### Example

Create a variable inside a function, with the same name as the global variable

x = "awesome"  
  
def myfunc():  
  x = "fantastic"  
  print("Python is " + x)  
  
myfunc()  
  
print("Python is " + x)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_global2)

---

---

## The global Keyword

Normally, when you create a variable inside a function, that variable is local, and can only be used inside that function.

To create a global variable inside a function, you can use the `global` keyword.

### Example

If you use the `global` keyword, the variable belongs to the global scope:

def myfunc():  
  global x  
  x = "fantastic"  
  
myfunc()  
  
print("Python is " + x)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_global3)

Also, use the `global` keyword if you want to change a global variable inside a function.

### Example

To change the value of a global variable inside a function, refer to the variable by using the `global` keyword:

x = "awesome"  
  
def myfunc():  
  global x  
  x = "fantastic"  
  
myfunc()  
  
print("Python is " + x)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_variables_global4)

---

## Exercise?

Consider the following code:  
`x = 'awesome'   def myfunc():     x = 'fantastic'   myfunc()   print('Python is ' + x)`  
What will be the printed result?

  

Python is awesome

Python is fantastic

  
Submit Answer »

# Python - Variable Exercises

---

## Test Yourself With Exercises

Now you have learned a lot about variables, and how to use them in Python.

Are you ready for a test?

[](https://www.w3schools.com/)

  

## Exercises

Test your Python Variables skills with exercises from all categories:

[

## Variables



](https://www.w3schools.com/python/exercise.asp?x=xrcise_variables1)[

## Variable Names



](https://www.w3schools.com/python/exercise.asp?x=xrcise_variables_names1)[

## Multiple Variable Values



](https://www.w3schools.com/python/exercise.asp?x=xrcise_variables_multiple1)[

## Output Variable



](https://www.w3schools.com/python/exercise.asp?x=xrcise_variables_output1)[

## Global Variable



](https://www.w3schools.com/python/exercise.asp?x=xrcise_variables_global1)

More Python Exercises:

[Python Exercises](https://www.w3schools.com/python/python_exercises.asp)

  

---

[❮ Previous](https://www.w3schools.com/python/python_variables_global.asp)[Next ❯](https://www.w3schools.com/python/python_datatypes.asp)

Track your progress - it's free!

[Log in](https://profile.w3schools.com/log-in?redirect_url=https%3A%2F%2Fpathfinder.w3schools.com&origin=https%3A%2F%2Fwww.w3schools.com%2Fpython%2Fpython_variables_exercises.asp "Login to your account")[Sign Up](https://profile.w3schools.com/sign-up?redirect_url=https%3A%2F%2Fpathfinder.w3schools.com&origin=https%3A%2F%2Fwww.w3schools.com%2Fpython%2Fpython_variables_exercises.asp "Sign Up to Improve Your Learning Experience")

[![Get Certified](https://www.w3schools.com/images/img_fa_up_300.png)](https://campus.w3schools.com/products/w3schools-full-access-course)

#### [COLOR PICKER](https://www.w3schools.com/colors/colors_picker.asp)

[![colorpicker](https://www.w3schools.com/images/colorpicker2000.png)](https://www.w3schools.com/colors/colors_picker.asp)

[](https://www.youtube.com/@w3schools "W3Schools on YouTube") [](https://www.linkedin.com/company/w3schools.com/ "W3Schools on LinkedIn") [](https://discord.com/invite/w3schools "Join the W3schools community on Discord") [](https://www.facebook.com/w3schoolscom/ "W3Schools on Facebook") [](https://www.instagram.com/w3schools.com_official/ "W3Schools on Instagram")

[](https://www.w3schools.com/)