# Arithmetic
You’ve probably heard that Math and programming have a lot in common. It’s
quite true since programming is based on Mathematics the same way Physics is.
It shouldn’t be much of a surprise to see a lot of Mathematics in programming.

Till now, we’ve seen strings being assigned to variables; but, just like in
maths we can assign integers to variables and do mathematical operations on
them.

A computer in its simplest form is a calculator and it can do everything that a
basic calculator(+, -, ×, ÷) can do (and it can do it really well). The only
difference between your calculator and Python is that we use * for
multiplication (×) and / for division (÷).

Note: Computers do follow BODMAS.

Let’s look at some examples:
```.py
x = 10 #Assign the variable x to the int 10!
print( (x+10) / 2 )  #Output:10
print( (x+10)*2 )    #Output:40
print( x + 10 - 5 )  #Output:15
```
We have one more function in programming called modulus, it is represented with
`%`. It gives the remainder when you are dividing two numbers.

Example:
```.py
print(5%2) #Output: 1; (5÷2 = 2 remainder 1!)
```

## Question

Eve wants to calculate the final price after a discount is applied on an order.
She is told that the total price is $150 and the amount of discount given is
25%. Calculate the price after the 25% discount and print this discounted price.
