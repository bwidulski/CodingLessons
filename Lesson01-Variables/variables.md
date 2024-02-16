# Variables

### What are Variables?

Variables represent a position in a computer's memory that holds some type of data. These data types can be a word ```string```, a whole number ```integer```, a decimal number ```float```, a letter/number ```char```, or a true/false value ```boolean```, to name a few. 

Variables are the base element used to hold all data in a program. They can be generically defined in the following way:

```python
<variable_name> = <variable_value>
```

Some actual examples would be:
```python
dogName = "Fred"             
dogAge = 4                   
dogWeight = 75.4           
dogSex = 'M'
isAlive = True                 
```

In Python, variables are ```weakly typed```, meaning they don't need an explicit data type definition. A ```strongly typed``` language, such as Java, would define these in the following way:

```java
String dogName = "Fred";
Integer dogAge = 4;
Float dogWeight = 75.4;
Char dogSex = 'M';
Boolean isAlive = True;
```

Python variables thus don't need their data types explicitly defined, as they are inferred when the program runs. Under the hood, the Python variables above are actually the same as Java, but this is obfuscated from the Python programmer.

This also means that these variables can be mutated at any point to hold any other data type. The following would be valid code in Python:

```python
dog = "Fred"
dog = 4
dog = 75.4
dog = "M"
```

In Java however, this would lead to a compilation error, as different data types can not be assigned to the same initially declared variable.

Variables can even be assigned to the value of other variables! Here's an example:

```python
dogName = "Fred"            
otherDogName = dogName   # otherDogName = "Fred"
```

