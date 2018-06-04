# And, Or, Not

There are three keywords that can let us work with boolean values much more
easily. These keywords are ‘and’, ‘or, and ‘not’.

The keywords ‘and’, and ‘or’ are used to join together boolean expressions. The
syntax is:

```
if condition1 and/or condition2:
	Statements
```

The keyword `‘not’` just changes a True condition to False and vica versa.
### Or
A customer wants cakes worth either $7 or $20.
```.py
If price == 7 or price== 20:
	print("Buy this cake!")
Else:
	print("The cake isn't for the price you specified.")
```

Or statements returns True if even one condition is True.
### And
The customer realized this condition isn't very logical. Instead of selecting
cakes at two drastically different price points, he now makes a range of
values. If the cake is more than $7 and less than $20, he'll buy it. This way,
he gets more options with the same amount of money!
```.py
if price > 7 and price < 20:
print("Buy this cake!")
else:
	print("This cake isn't within your range")
```

And only returns True if both the statements are True.

### Not
Another customer walks in. This one want fancy cakes and won't buy anything
below $25
```.py
if not (price<25):
print("You can buy this cake!")
else:
	print("This cake is below your price range")
```
The not keyword is used to flip the boolean value. If the condition is false,
the boolean is true, and vice versa.

## Question
Eve needs to be at the bakery from 12:00 to 20:00, and she has asked you to
write a program for her friends to check if she’s free or not. So, if her
friends input 8 (for 0800), the output would be
“Eve is not free at 8”.
Meanwhile, if the input is 2pm or 14:00
Print the output for 1pm (or 13:00, input would be 13)

**Note:** To input integer value you need to inclose the input function inside
int()

Example:

`number = int(input("Enter a number:")`
