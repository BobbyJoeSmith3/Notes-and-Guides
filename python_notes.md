Python Notes
============

###Variables
Creating web apps, games, and search engines all involve storing and working with different types of data. They do so using **variables**. A **variable** stores a piece of data, and gives it a specific name.

For example:

```spam = 5```

The variable ```spam``` now stores the number ```5```.


###Booleans
Great! You just stored a number in a variable. Numbers are one data type we use in programming. A second data type is called a **boolean**.

A **boolean** is like a light switch. It can only have two values. Just like a light switch can only be on or off, a boolean can only be ```True``` or ```False```.

You can use variables to store booleans like this:

```
a = True
b = False
```


###Whitespace
In Python, whitespace is used to structure code. Whitespace is important, so you have to be careful with how you use it.

###Multi-Line Comments
The ```#``` sign will only comment out a single line. While you could write a multi-line comment, starting each line with ```#```, that can be a pain.

Instead, for multi-line comments, you can include the whole block in a set of triple quotation marks:

```
"""Sipping from your cup 'til it runneth over,
Holy Grail.
"""
```

###Math
Great! Now let's do some math. You can add, subtract, multiply, divide numbers like this

```
addition = 72 + 23
subtraction = 108 - 204
multiplication = 108 * 0.5
division = 108 / 9
```


###Exponentiation
All that math can be done on a calculator, so why use Python? Because you can combine math with other data types (e.g. **booleans**) and commands to create useful programs. Calculators just stick to numbers.

Now let's work with exponents.

```eight = 2 ** 3```

In the above example, we create a new variable called ```eight``` and set it to ```8```, or the result of ```2``` to the power to ```3 (2^3)```.

Notice that we use ```**``` instead of ```*``` or the multiplication operator.


###Modulo
Our final operator is **modulo**. **Modulo** returns the remainder from a division. So, if you type ```3 % 2```, it will return ```1```, because 2 goes into 3 evenly once, with 1 left over.


###Bringing It All Together
Nice work! So far, you've learned about:

- **Variables**, which store values for later use
- **Data types**, such as numbers and booleans
- **Whitespace**, which separates statements
- **Comments**, which make your code easier to read
- **Arithmetic operations**, including ```+```, ```-```, ```*```, ```/```, ```**```, and ```%```