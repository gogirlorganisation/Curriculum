# Control Flow - If and Else
Eve wants to bake a cake! Her mother told her that the cake needs to be in the
oven for 25 minutes. So,
```
if the timer is equal to 25 minutes:
	Eve needs to take out the cake!
```
If statements use conditionals to decide whether or not a certain block of code
is executed. So, if the condition is true, then the statements are executed;
The syntax looks like this:
```.py
timer = 25
if timer == 25:
	print(“Eve took out the cake”)
```
In this case, since the condition is true, the output will be: Eve took out the
cake

However, if the value of timer is not 25 then the printing code won’t run.

**Note:** The white space before the print block indicates that the print is
part
of the if block. This is called indentation and is crucial in Python syntax.
This can be keyed into your code by the Tab key on your keyboard.
```.py
timer = 15
if  timer == 25:
	print(“Eve don’t take out the cake”)
```
In this case, there would be no output as the condition, timer == 25 , is not
met.

### Else
Else statements are used to execute a block of code when the condition for the
if statement is False.
```.py
if timer is equal to 25:
	Tell Eve to take the cake out
else:
	Tell Eve not to take the cake out
```

We can write it like this in Python:

```.py
if timer == 25:
	print(“Take the cake out of the oven”);
else:
	print(“Leave the cake in the oven”)
```

## Question

Eve is managing the counter today. She loves even numbers more than odd, so she
has decided that she will give a free toffee to all the bill values which are
even.

Declare a variable bill which takes in user input. If the customer is eligible
for the toffee, print ‘Here is a free toffee! Have a nice day!’. Otherwise,
print ‘Have a nice day!’

For example, if the input is 155, the output should be “Have a nice day!”

Now, enter an even value for the bill and see what it prints!
