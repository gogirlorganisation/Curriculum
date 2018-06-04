# Lists

Eve’s mom wants her to go grocery shopping for their bakery, so, she makes a
list of all the items she needs. Her list contains the following items:

1. Butter
2. Milk
3. Chocolate
4. Bread

Python offers a tool called lists to keep track of related "things," or values.
To help Eve, let's make a list called shopping_list  and fill it with each of
the items:

`shopping_list = [“Butter”, ”Milk”, ”Chocolate”, “Bread”]`

**Note:** We use square brackets to create a list. Each item in the list is
separated by a comma!

To call and check an item in the list, we use the following format:

`shopping_list[item_number]`

This looks familiar to indexing in strings, doesn’t it? That’s because it works
the exact same way. We can call a specific item in the list by typing the name
of the list, then entering the item’s position inside square brackets ([]),
Now, let’s try to print the first element from the list and seeing if it prints
Butter:

	`print(shopping_list[1])`

Try and run this. Did it return “Butter”? Nope, It printed Milk, didn’t it?
That’s because, just like for strings, Python starts counting from 0. If we
want to print the fourth item in the shopping_list (bread) we can do so like
this:

`print (shopping_list[3])`

**Output:** Bread
Even though Bread is the 4th item, it’s index position is 3.

Eve forgot to add flour to her list! Oh no, how will she bake her cake now?
Fear not...you can add flour to her shopping list since there’s no limit for
the length of the shopping list.

The syntax for adding a new element to the end of the list is:
```.py
list_name.append(item)

shopping_list.append(“flour”)
```
Now using `.append()`, the item can only be added to the end of the list. But do not fret, we can add the item to whichever position you like using another
function **insert()**

```.py
list_name.insert(index number, item)

shopping_list.insert(1,”flour”)
```
Within the brackets first mention the desired  *index number*  and then the
item.

Eve realised she doesn’t need 2 packets of flour! Let’s replace the last flour
with toffees!

```.py
list_name[index] = element

shopping_list[5] = “Toffees”
```

Sometimes you need to remove something from the list, that can achieved by yet
another function **remove()**.
Silly Eve forgot she already had a loaf of bread at home, so she needs our help
to remove that item from the list.

```.py
list_name.remove(element)

shopping_list.remove(“bread”)
```

## Question
Eve’s shopping list has the following items:
* Milk
* Eggs
* Flour
* Apples
* Orages

In that specific order. Add these items to a list and print ‘Flour’ from the
list.
