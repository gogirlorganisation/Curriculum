# Loops - For

What’s the laziest thing, creature, or entity to have ever existed?
Is it a sloth? A slug, maybe?
No...it’s a programmer!

Is there really anything worse than writing the same code again and again and
again and again?
A customer places an order for a 100 cupcakes. Eve needs to make a receipt for
the purchase. So, she wants <code> print (“Cupcake $2.40”) </code> 100 times,
she’s not going to repeat this code a 100 times. Instead, she’ll use a new
feature- ** loop .**

```
For variable in range(0,numberoftimes):
	code
```
```.py
for x in range(0,100):
  print(“Cupcake $2.40”)
```
Here, the variable x will go (i.e. iterate) from 0-99, printing **Cupcake
$2.40** each time it completes one iteration.

**Note:** Like slicing, the first value is inclusive whereas the second value
is exclusive thus the value of x changes from 0 - 99 and not from 1 - 100.

Eve needs to count the number of eggs, thus she needs the computer to print
numbers from 0 to 15.You can print numbers between 2 numbers by just adjusting
the range. In this case it would be

```.py
for x in range(0,16):
print(x)
```
**Note:** Keep in mind that the the values of x will vary from the first
number till the (last number - 1)

Let’s apply the if-else statements we learned earlier to loops.
Suppose we want to check which numbers between 1-10, are even  and which are
odd. Then it will be done in the following way:
```.py
For x in range(1,10):
	If ( x%2 ==0)
		print (“even”)
	else
		print(“odd”)
```

## Question

Eve loves prime numbers but she finds it really hard to determine if a number
is prime or not. She wants to use her programming skills to determine is a
number a prime or not.

She comes up with a very basic condition, if she can find a factor of the
number other than 1 and itself then it’s not prime. She wants to use a for
loop to make a variable x iterate from 2 till the number itself using the
inbuilt function, and use if condition to check if the number is divisible by
x then she knows its prime.

Check if 169 is a prime, if it is print `"prime"` if not print `"not prime"`.
