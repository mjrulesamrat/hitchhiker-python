# Lesson 1 / Whitespace

## Tasks
- Learning the importance of whitespace in Python

## Get Started
In Python, whitespace is used to structure code. Whitespace is important, so you have to be careful with how you use it. Whenever your whitespace is off, you'll get this error.
```
IndentationError: expected an indented block
```
Example
1. Create a file `whitespace.py` with the following content
```py
def spam():
eggs = 12
return eggs
        
print spam()
```
2. In the terminal run the following command
```shell
python whitespace.py
```
3. You must see the error printed in the terminal.

## Let's improve the indentation
1. Update the file `whitespace.py` with the following content
```py
def spam():
  eggs = 12
  return eggs
        
print spam()
```
2. In the terminal run the following command
```shell
python whitespace.py
```
3. You must see `12` printed in the terminal.

In this tutorial, we will use two-space indentation (two blank spaces for each indentation) to make sure you can easily read code with multiple indentations. You will also see Python code that uses four-space indentation. Both are correct, as long as you make sure to be consistent throughout your code.