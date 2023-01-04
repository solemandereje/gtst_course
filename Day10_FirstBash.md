# Introduction To Bash Scripting

# Today's Topics

- what is bash,
- use of bash for hackers
- Output,
- variables & data type
- Input
- comment and indentations
- Arithmetic operation
- if-else

# What is Bash Script?

- Bash = Bourne Again Shell
- It is a shell, that used to interact with your
  kernel.
- What is Script?
  > - Script is a file that contains shell commands.
- The original is sh - Bourne shell

# Uses of bash

- Script development
- Simplifying tasks
- Simplifying your linux ability
- Developing hacking scripts.

# Starting with Bash

- Bash files can have “.sh” extention but you can have it with out .sh too
- The file have to have executable Permissions.
- You can use any text editors u need: VIM,nano,VScode,gedit,cherry

# Displaying output

- To start Every bash scripts use shebang.
  > - #! /bin/bash
  > - #! /bin/sh
- To display outputs on bash you just do
  > - echo “YOUR TEXT HERE”
- To run your project you can do:
  > - /bin/bash hello.sh
  > - ./hello.sh -> need x
  > - hello -> need x
- f you need to add new lines on ur code just
  add **echo**

# Variables

- Bash Variables are same with python variables, with some exceptions.
- Syntax:
  > - VARIABLE_NAME=value
- Exceptions:
  > - NO Space between the equal sign ( = )
  >   > - NAME = “Nathan” => ERROR
  >   > - NAME=”Nathan” => Correct.
  >   > - Never Start with Numbers
  >   > - USE double quotes only.
- To use the variable we will use dollar sign( $ ) before the Variable name
- If you want to display the variable sticked with other text use ${VARIABLE_NAME}
- Bash Variables are string by default.
- The set command can be used to assign values to positional parameters.
- Syntax:
  > - set value1 value2 value3 value4 value5

# System Variables

- Are variables those are declared by the system
- There are so many: LANG, TERM,MAIL,EDITOR,USER,SHELL….
- USER displays Computer owner(host)

# Variables & Data Types

- As we saw, the previous method they create strings only.
- So to create other data types we use declare.
- Arrays \
   a. Arrays are lists or tuples on python. \
   b. Syntax:
  > i) var=(“list1” “list2” “list3” “list4) \
  > ii) TO display echo
  > (1) ${var[0]}
  > iii) To get all the elements
  > (1) ${var[@]}
  > iv) To get the indexes
  > (1) ${!var[@]}
  > v) To get the length
  > (1) ${#var[@]}
  > vi) To add element to the array
  > (1) var[4]=”list5”
  > vii) To remove from the array
  > (1) unset var[3]
  # Bash Input
- On bash we have 2 methods to accept input

1. Read function
2. Arguments

# 1) Bash read

- Read used to accept inputs while the script is running.
- Syntax:
  > - read -p “Text To Display” var
  > - read -sp “Password: ” var => used to accept hidden texts like password.
  > - read -a var => for accepting arrays

# 2) Arguments

- These helps to get input before the script starts
- Syntax:
  > - Just use $0-$9 while you want to work with the input

# Comments

- On bash the comments are
  > - #this is a comment
  > - For multi line comment we start with
  >   **<<COMMENTS** \
  >   Sfasf \
  >   Sfa \
  >   **COMMENTS** , we close with this
  # Bash sleep
  - Sleep used to make a good waiting on our script.
  - Syntax:
    > - sleep <number>s

# Operation

- To do mathematical operations you have to do $(( expression ))
- we will use let keyword for assigning variable \

## A) Arithmetic Operations \

a) Addition $(( a + b )) \
 b) Subtraction $(( a - b )) \
 c) Multiplication $(( a \_ b )) \
 d) Division $(( a / b ))
e) Exponential $(( a \*\* b ))
f) Modulo $(( a % b ))

## B) Assignment Operations

a) Increment “let a+= 3”
b) Decrement “ let a-= 3”
c) Multiply “ let a\_= 3 “
d) Divide “ let a/=3 “

## C) Comparison operation

### Alphabetic comparison

- Greater Than => -gt
- Less Than => -lt
- Greater than and equals to => -ge
- Less than and equals too => -le
- Equal => -eq
- Not equal => -ne

### Sign comparison

- \>
- <
- \> =
- <=
- =
- !=

# if else conditions

- syntax
