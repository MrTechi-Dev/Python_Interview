# Hello everyone! I'm building this documnent to help community to get through the Python Developer Interviews.

### The following are the most common questions in a technical interview, but bare in mind it might be just be an overview therefore do not depend only from this source for your technical interview.

## You are very welcome to add information here, just let me know.

## Let's go ahead and have fun!

### Python core questions:

* [What is the GIL of Python](https://realpython.com/python-gil/)
* [Python garbage colector](https://stackify.com/python-garbage-collection/)
* [Python concurrency or paralelism](https://stackoverflow.com/questions/2150144/is-python-a-serious-option-for-concurrent-programming)

* [The C of Python CPython](https://en.wikipedia.org/wiki/CPython)
* [What is Python library](https://www.mygreatlearning.com/blog/open-source-python-libraries/)

*  [What are theDesign Patterns](https://refactoring.guru/design-patterns)
* [Objects oriented programming](https://realpython.com/python3-object-oriented-programming/)

* [Are strings in python muteable or inmuteable](https://stackoverflow.com/questions/9097994/arent-python-strings-immutable-then-why-does-a-b-work)

* [what is an iterator](https://www.mygreatlearning.com/blog/iterator-in-python/)
* [What is generator function](https://www.tutorialsteacher.com/python/python-generator)
* [What is composition in Python](https://realpython.com/inheritance-composition-python/)

### Python decorator:
Sample:

super_secret = "2323"

def wrapper(func):
    password = input
    if password == super_secret
        return func
    else:
    return ("No Pass")
return wrapper

@password
def need_password():
    print(password ok)

if__name__==main:
need_password()

### Dict comprenhestions:
from math import sqrt

def run():
    my_dict = {}

    for i in range(1, 101):
        if i % 3 != 0:
            my_dict[i] = i**3

    print(my_dict)


def run2():
    
    my_dict = {i: i**3 for i in range(1, 101) if i % 3 != 0}

    print (my_dict)

if __name__ == '__main__':
    run()
    run2()

## List comprenhension:
def run():
    squares = []
    for i in range(1, 101):
        if i % 2 != 0:
            squares.append(i**2)

    print(squares)
def runn():
    squares = [i**2 for i in range(1, 101) if i % 2 != 0]
    print(squares)

def reto():
    squares = [i for i in range(1, 100) if i % 4 == 0 and i % 6 == 0 and i % 9 == 0]
    print(squares)


if __name__ == '__main__':
    run()
    runn()
    reto()
### Python data types: 

int: 1

string "andres"

List:
list = [1, 2 ,3, "hola"]

Dictionary:
dict = { "key": "value}

Tuple:
(1, 2, 3. "Hello")

Boolean:
True or False


### List functions:
*append
*count
*extend
*index
*insert
*pop
*remove
*reverse
*sort
*id
*len

#### Samples:
*round (6,3456)
=>  6,3

* range (3)
=> [0, 1, 2]

sum ([1, 2, 3])
=> 6

### Map:
map(str, [1, 2, 3, 4])
=> ["1", "2", "3", "4"]

### Zip:
x = [1, 2, 3]
y = [ 4, 5, 6]

zipped = zip(x, y)
list(zipped)
=> [1, 2, 3, 4, 5, 6]

## Conversors:
int (4,3)
=> 4

floar(4)
=> 4.0

str (4,3)
"4,3"

## Sorted vs Sort function:
data.sort()
=> sorted data in a new instance

sorted(data)
=> sort data in the same instance

