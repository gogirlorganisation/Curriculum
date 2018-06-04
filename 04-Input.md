# Input
Up to this point, we’ve learnt how to make the computer display things and give
us various outputs. Now, we will learn how to feed information into the
computer.

Python has an interesting feature called `input()`. Judging from its very name,
`input()` is pretty self explanatory. When the program runs and it reaches a
line with `input()` on it, it stops and waits till the user inputs in a value
into the computer. This input can then be saved to a variable.

**Example:**
```.py
print(“What’s your name?”)
name = input() # waits till the user enters an input
print(“Hello!”)
print(name)
```

In this above example, we create a variable called ‘name’ and request the
computer user to input a name into the computer. After the user inputs a name
and presses the Enter key on their keyboard, whatever name they have written is
automatically saved to the created variable, ‘name’.

## Question
Eve wants to automate the computer in her bakery to greet her customers. Write
a program which asks the customer for their name and then greets them in the
following format:
```
“Welcome to the bakery,”
“Eve” #This is the inputted name!
```
