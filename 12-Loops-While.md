# Loops - While
Eve has had a hard day at work at the bakery today.So, she wants to take a nap.
She’s told her mum not to disturb her  **while** she’s sleeping. Once  she
wakes up, her mother can give her chores.Her request condition expires or, is
terminated, once she wakes up and is no longer sleeping.
```
While eve is sleeping:
		Don’t disturb her
```
This is the basic principle of a **While Loop**. The while loop tells the
computer to do something as long as **the condition** is met.

The condition is evaluated, and if the condition is **true**, the code within
the block is executed. This repeats until the condition becomes false.

The syntax for while loop is:
```
while [a condition is True]:
    [do something]
```

Eve can’t sleep, so she decides to count sheeps till 25. Let’s try printing
values from 1 till 25 using a while loop.
```.py
sheep_counter = 1
while sheep_counter < 26:
		print(sheep_counter)
```

Oh no! What happened, the computer is just printing 1 and is not even stopping!

Don’t worry, you are just stuck in an infinite loop as the condition
sheep_counter which has a value of 1 is less than 26 is always True! Let’s
update the value of the sheep_counter after each iteration.
```.py
Sheep_counter = 1
While sheep_counter < 26:
print(sheep_counter)
sheep_counter = sheep_counter + 1
```
