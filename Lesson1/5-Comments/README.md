# Lesson 1 / Comments

## Taks
- Learning single line and multiline comments in Python

## Get Started
The `#` sign is for comments. A comment is a line of text that Python won't try to run as code. It's just for humans to read.  
Comments make your program easier to understand. When you look back at your code or others want to collaborate with you, they can read your comments and easily figure out what your code does.
## Single line comments
Example:
```py
def spam():
  eggs = 12 # Assign number of eggs to 'eggs' variable
  return eggs
        
print spam()
```
## Multi line comments
Example:
```py
def spam():
  eggs = 12
  """Let's return the value stored in eggs
  so that it can be used further
  """
  return eggs
        
print spam()
```