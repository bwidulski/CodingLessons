# Objects

### What are Objects?

Objects are essentially items in a program. Nearly everything that's used is some type of object or related to one. For example, each of the data types are actually objects. ```String``` ```Integer``` etc. are all objects.

Objects have a few different attributes, the first of which would be called elements. Elements are essentially variables inside of objects that hold some information about them.

Let's say we had an object, ```ball```. A ball could have a few different elements, such as it's color, it's size, whether it's bouncy or not. All of these variables would be held within the object

These elements can typically be accessed through a ```dot operator```. Here's an example with our ball object:

```python
ball.color          # returns "Blue"
ball.size           # returns 2.5
ball.isBouncy       # returns True
```

Objects can also have methods, declarations that tell that object to do something. These are also typically accessed through the ```dot operator```. Here are some examples:

```python
ball.roll()         # makes the ball roll
ball.bounce()       # makes the ball bounce
ball.stop()         # makes the ball stop moving
```

