# String Operations

We’ve been talking a lot about working with numbers, so now, we’ll be talking
about what are the things you can do with strings!
### Concatenation
Earlier, we learnt about strings as collections of characters. Concatenation is
a way of joining multiple strings together. You can easily add strings to build
a complete sentence by using the addition operator - i.e. the ‘+’ sign. Crazy,
right?

Example:
```.py
str01 = “ginger”
str02 = “bread”
str01 = str01 + str02
```

Now, str02 will also be added to str01, meaning str01 now reads: gingerbread.
Thus, we have concatenated str01 and str02.

P.s: Do not use this in your examination! We don’t want your English teacher to
faint!

### Uppercase and Lowercase
There is a handy feature in Python that helps convert the characters in a
string to uppercase or lowercase. Let’s look at an example to show you how it
works.
```.py
str01 = “GiNgEr”
str01 = str01.upper()
print( str01)
print( “BrEaD”.lower() )
```
The output looks like this:
```
GINGER
bread
```
You can see how adding `.upper()` or `.lower()` to a variable or to a string
can change its case.

### Length of Variables
What do you do if you want to know the length of a string? We know that the
word ‘Hello’ contains 5 letters.

Instead of counting each letter, we can let the computer do it for you. All you
need to do is use a function called len().

`len(“Eve likes to go shopping during the weekends”) `

Output: 44

**Note:** `len()` function counts spaces too!

Did you notice something strange? 44 is not printed on the screen. That’s
because you haven’t called the print function to do it for you! Go ahead and do
it!

You can use it with variables too!

```.py
greetings = “Hello”
Length_of_greeting = len(greetings)
print(Length_of_greeting)
```
Output: 5
### Indexing
`H E L L O `

Eve wants to print the letter at the second index position in "HELLO".
Can you help her do that? For accessing specific letters in a string we have to
write the following

`String[postion_of_the_letter]`

For example:
```
word = “HELLO”
print(word[2])
```
The output is:

L

That shocked you, didn’t it?! Although L is the third letter in the word HELLO,
it is in the **second index** position.

Programmers are weird like that. They like to count from 0. Look at the image
attached to get a better sense. Now think about which letter you would get if
you printed the fourth index position.

The answer is:

O

Yes! You did it! O is the fifth letter but has the fourth index position
assigned to it.
### Slicing
`amazing_programmer = "Ada Lovelace"`

Phew...that’s a **long** name! Eve wants to just print out the first name. How
would she do that?

To get a part of a string we need to write:

`Variable_name[starting_index : ending_index]`

A is at index position 0 and the 2nd A is at index position 2. To print out
"Ada", we need to write

`print(amazing_programmer[0:3])`

You might be wondering why we used 0:3 instead of 0:2. That’s because the first
index number is inclusive (includes that position) and the last index number is 
exclusive (doesn’t include that position). In other words, the sliced string
only includes characters up to the character before the ending index.

Now, Eve wants to print out “Love”. Can you try to do that for her?
Done? Here’s the answer:

`print(amazing_programmer[4:8])`

Wondering why it isn’t 3:8? That’s because we count a space “ “ as one position
too! So, L comes at the 5th index position.

Got it? Good!
