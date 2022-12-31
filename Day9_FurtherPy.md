# Further on Python

# Topics

- Functions,recursion
- lambda → Map/filter
- OOP & POP
- Class & objects
- user-built Module

# Functions

- A function is a block of code that performs a specific
  task.
- Suppose, you need to create a program to create a
  circle and color it. You can create two functions to solve this problem:
  > - create a circle function
  > - create a color function
- Dividing a complex problem into smaller chunks makes our program easy to understand and reuse.

## Types of function

- There are two types of function in Python programming:
  > - Standard library functions - These are built-in functions in Python that are available to use.
  >   > - Almost all keywords are functions
  > - User-defined functions - We can create our own functions based on our requirements.
  ## Creating FUnctions
  - Syntax: It have body like if else statements also have
    body
    > def function_name(): \
    >
    > > #function body

## Function Arguments

- They are used to take value while calling and insert it inside the function
- syntax:
  > def add_numbers(num1,num2): \
  >
  > > sum = num1 + num2 \
  > > print(sum) \
  > >  #function call with two values
  > > add_numbers(5,4) \
  > > #output : Sum :9

## Return statement

- A Python function may or may not return a value.
- If we want our function to return some value to a function call, we usebthe return statement
- syntax:
  > def add_numbers(): \
  >
  > > ..... \
  > > return sum
- As i told you every things are functions on python
  > - So print() is function also input() is len(), everything
  > - When we do we are calling the function and giving it an argument.
- You can give default values too

# Recursion

- Recursion is process of defining something in terms of itself.
- In Python, we know that a function can call other functions. It is even possible for the
  function to call itself. These types of construct are termed as recursive functions.
- syntax 👍
  > def recurse(): \
  > ... \
  > recurse() \
  > .....
  > recurse()

## Advantages of Recursion

1. Recursive functions make the code look clean and elegant.
2. A complex task can be broken down into simpler sub-problems using
   recursion.
3. Sequence generation is easier with recursion than using some nested
   iteration.

## Disadvantages of Recursion

1. Sometimes the logic behind recursion is hard to follow through.
2. Recursive calls are expensive (inefficient) as they take up a lot of memory and time.
3. Recursive functions are hard to debug

# Anonymous / lambda Function

- If function doesnt have name it is called lambda function / Anonymous
- If you have 1 line code to return you dont need to def a function,
- a lambda function is a special type of function without the function name.
- Syntax:
- We use lambda key

## Function takers function

- Filter, map & reduce takes a function as an argument.

## Filter Function

- Filters are used to filter or search some function from sequences.

## Map function

- Used to do some operations on Sequences

## Append

- Append used to add some value to a list.
- Syntax:
  > my_list.append(new value)

# Object-Oriented Programming / OOP

- Python is an object oriented programming. This means mores things on python are
  objects.
- Objects are anythings which can have action and name.
- Objects have attributes(properties) and methods(action or functions)
- Example : My COmputer
  > > - Attribute: name,size,cpu,ram…
  > > - Behaviour: Running games, playing music, displaying

## Python class and object

● Class is simply a place where we create our Object’s attribute and behaviour in blueprint
● a class is a blueprint for that object.
● Syntax:

> class computer:
>
> > #creating atribute \
> > name="" \
> > cpu=""

- After you create the Blueprint, now you can create the objects
  > #creating object based on the blueprint
  >
  > > john_computer=computer()
  > > john_computer.name="hp laptop"
  > > john_computer.cpu="intel core i5"

## Creating Objects

- You can Create many Objects based on 1 class. | Here we created Object
  called Nathan_Computer
- Syntax:
  > - Var = classname()
  > - Var.attribute = “value”

## Lets check the type() of our object

- When we check Our type it is similar with type of int, both
  are classes,
- ‘a’ and ‘Nathan_Computer’ are objects
- computer and int are classes
  > john_computer=computer()
  > print(type(john_computer))
  >
  > > #output= class

## Giving Behaviours == Creating Methods

- Functions are called methods on OOP
- Syntax on calling
  > > - classname .method(object)
- Creating a Behaviour run, which is 1 behaviour of my
  computer. And have parameter of ‘self’
- Self is the object name on OOP you have to declare it.

# Python Constructors

- Earlier we assigned a default value to a class attribute,However, we can also initialize values using the constructors.
- Here, \***\*\_\_init\_\_\*\***() is the constructor function that is called whenever a new object of that class is instantiated.
- The constructor above initializes the value of the name attribute. We have used the self.name to refer to the name attribute of the bike1 object.
- If we use a constructor to initialize values inside a class, we need to pass the corresponding value during the object creation of the class.
- syntax:
  > class Bike: \
  > #constructor function \
  > def \_\_init\_\_ (self, name=""):
  >
  > > slef.name = name
  > > bike1=Bike()

# Python Inheritance

- Is a way of creating new class with
  some properties of existing class.
- Syntax:
  > - class newclass(oldclass)

# Python Encapsulation

- Encapsulation is Feature of OOP, That refers to
  bundling of attributes and methods inside a
  single class

# Package installing

- As we have seen package installing on our linux tutorial.We use pip to install tools so, on terminal
  > pip install packagename

# Package using

- On python, there are a lot of packages to use them, we simply
- Each packages have their own classes and methods so we have to do more studies about
  those packages.
