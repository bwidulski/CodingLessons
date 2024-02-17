# Conditionals

### What are Conditionals?

Conditionals decide the path that code takes based off a statement's truthfullness. They are used when the programmer is unsure exactly what the value of something will be and they must route their code accordingly.

There are a few different types, but we'll first start with ```if statements```

### Keywords

All programming languages have something called ```keywords``` - Operators that are reserved for use by the programming language, and can not be used in any other context. The three keywords related to if statements are ```if```, ```elif```, and ```else```. 

This means it would be invalid in Python to do something like:

```commandline
if = else
```

### If Statements

The three parts of Python's if statements are:

- ```if```: The first part of the if statement. It is entirely necessary in any if statement to use this. If it's statement is evaluated to equal ```True```, then it will execute the code below it. If it evaluates to ```False```, then the next block of code will be executed
- ```elif```: This will be used in the case that there is another specific statement to be evaluated and is not necessary in an if statement. It behaves the same way as if.
- ```else```: This will be executed in the case that all other statements evaluate to ```False```. It can be used as a catch-all for anythign that falls outside the expected scope of conditional outcomes.

As an example:

```python
if dogName == "Fred":
    dogOwner = "Bobby"
elif dogName == "Rex":
    dogOwner = "Kevin"
else:
    dogOwner = "?"
```

There are a few things to point out here. The first is the operator ```==```. This is an operator used to check if one object exactly equals the value of another. It evaluates to one of two values: ```True```, in the case that the objects are equal, or ```False``` otherwise. 

These statements will evaluate to true:
```python
"dog" == "dog"
14 == 14
dogAge == 4
```
While these statements will evaluate to false:
```python
"dog" == "cat"
17 == 4
dogAge == 6
```
One special case is:

```python
7.4 == 7.4
```

What do you think the outcome of this evaluation would be? If you guessed true, you'd actually be incorrect! Because of the way that decimal points are stored in a computer, there is a slight rounding error on all floating point numbers. This means that using a direct ```==``` comparison between two floats may not turn out how you expect it to. The first 17.4 could actually be equal to 17.40000000000023 while the second is 17.40000000000021

The second important thing in the conditional above is the ```:``` after each of the conditional statements. This is necessary for Python to compile and run your code, and indicates the beginning of a new code block.

In the same vein, the ```whitespace``` is also important. ```whitespace``` in Python is equal to 1 tab or 4 spaces. It is necessary to indent a code block in order for the compiler to understand that this is to be executed according to the above statement
