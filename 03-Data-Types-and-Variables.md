# Data Types and Variables

Just like your brain, the computer also has memory where it stores data (pieces
of information). These data come in many various types, which we will be
talking in just a minute.

Eve wants to create a receipt for her customer. The receipt includes three
things: The product's name, number purchased, and the total price.

Product   | Number Purchased | Total Price
--------- | ---------------- | -----------
"Cupcake" | 5                | $2.5

Eve's receipt above includes three different types of information. These three
things on Eve's receipt represent three different types of data: string,
integer, and float.

Looking the product section of the receipt, "Cupcake" is one example of a
string. Up to this point, you may be wondering why we're putting words in
quotes(" "). Any characters in between these is called a string, you can type
many characters in between these quotation marks to form words and sentences.

```.py
print("Hello! My name is Eve and I help run a family bakery")
```

For Number Purchased, the number 5 is stored. This number's type is called int,
which stands for integers. The integers in Python are essentially the same as
the ones you've studied in Math - whole numbers. Just like strings, you can
print ints as well!

`print(5)`

**Note:** Notice how "" aren't used here? That's because it's an integer and
not a string.

Lastly, looking at the Total Price, the number 2.5 is of another data type
called floats. These numbers are different from integers in that they have a
fractional value; a number with a decimal point. Like integers, they aren't
enclosed within quotes.

`print(11.22)`

### Variables

We've talked about the different kinds of data that exist in Python, but how do
we get the computer to save this data? In order for the computer to do so, we
need to make use of something called variables.

A variable can also be called a label for data. It serves three primary
functions:

1. **Store information:**

  Eve decides that she wants to buy a chocolate. Let's create a variable named
  "what_eve_wants" and store a string in it.

  `what_eve_wants = “Chocolate”`

  The left hand side contains the name of the variable you wish to create,
  whereas the right hand side contains the data you wish to store in this
  variable.

  **Note:** You can see an `=` sign being used. Just like we assign values in mathematics with `=`, we do the same in Python.

2. **Being able to take out that stored information:**

  Eve wants to display this information to others.

  `print(what_eve_wants)`

  Using variables is an easy and convenient way of storing and using data.

3. **Edit stored information:** Eve changes her mind and now wants ice cream. `what_eve_wants = “Ice cream”`

  **Note:** Here we see that we changed the value of what_eve_wants to "Ice
  cream". You can assign new values to old variables. The computer will
  remember the latest value that you have assigned.

  Go ahead and try in your compiler!

However, you need to keep in mind that variable names have to follow some rules:

1. Variable names must start with a letter or an underscore.
2. Variable names can only contain numbers, letters or underscores.
3. Variable names are case sensitive.

Valid     | Invalid
--------- | -------
\_hello    | 1hello
hello_123 | hello$
HELLO     | $$hello

Meanwhile, hello and Hello are 2 different variables. Be sure to be careful when you type!

## Question

Eve is confused between what type the following are. Print out your answers as either `"String"`, `"Float"` or `"Integer"` on different lines.

```
14.0
14
“Eve”
3.14
“14”
```
