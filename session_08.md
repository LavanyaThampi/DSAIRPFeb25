# Functions in Python
Functions are the basic building blocks of a Python program. A function in Python is a block of code that performs a task and can be called multiple times.
Funcions are two types
Built in functions and custom functions
## Built-in Functins
Type conversion function
eg:
list("äbc")
ouput
['ä', 'b', 'c']

dict([(1,"one"), (2,"two")])
ouput
{1: 'one', 2: 'two'}

tuple([1, 2, 3, 4])
output
(1, 2, 3)

bool(0)
False

bool(1)
True

set([1, 1, 2])
output
set{1, 2}

int("100")
100

float(3.14)
3.14

list("123")
['1', '2', '3']

tuple([4, 5, 6])
(4, 5, 6)

list((4, 5, 6))
[4, 5, 6]

str(25)
'25'

### Input/output function
n = input("Enter the name:")
print("Hello {} !". format(n))
output
enter the name:lavz
Hello lavz !

print("Python is fun!")
output
Python is fun

n = int(input("Enter value 1:"))
m = int(input("Enter value 2:"))
print(n+m)
output
Enter value 1:2
Enter value 2:3
5

a = input("Enter a sentence")
len(a)
output
Enter a sentenceyoyo
4

age = int(input("Enter the birth year:"))
print("age", 2025-age)
output
Enter the birth year:2000
age 25

### Mathematical Function
abs(-5)
5

pow(2,3)
8

round(3.7)
4

divmod(10, 3)
(3, 1)

abs(-15)
15

pow(2, 5)
32

round(4.6)
5

divmod(19, 4)
(4, 3)

sum([10, 20, 30])
60

len([1, 2, 3])
3

max(4, 7, 2)
7

min([10, 20, 30])
10

sum([1, 2, 3])
6

sorted([3, 1, 2], reverse=True)
[3, 2, 1]

sorted([3, 1, 2]), reverse=False)
[1, 2, 3]

tuple(range(5))
[0, 1, 2, 3, 4]

(0, 1, 2, 3, 4)

len([5, 10, 15])
3

max(12, 7, 19, 3)
19

min([12, 7, 19, 3])
3

sorted([8, 2, 5, 1])
[1, 2, 5, 8]

list(range(1,6))
[1, 2, 3, 4, 5]

isinstance(sum,int)
False

isinstance(a, int)
False

type("hello")
str

x = 42
id(x)
10752168

type(7)
int

type(3.14)
float

### Object and memory function
dir (list)
['__add__',
 '__class__',
 '__class_getitem__',
 '__contains__',
 '__delattr__',
 '__delitem__',
 '__dir__',
 '__doc__',
 '__eq__',
 '__format__',
 '__ge__',
 '__getattribute__',
 '__getitem__',
 '__getstate__',
 '__gt__',
 '__hash__',
 '__iadd__',
 '__imul__',
 '__init__',
 '__init_subclass__',
 '__iter__',
 '__le__',
 '__len__',
 '__lt__',
 '__mul__',
 '__ne__',
 '__new__',
 '__reduce__',
 '__reduce_ex__',
 '__repr__',
 '__reversed__',
 '__rmul__',
 '__setattr__',
 '__setitem__',
 '__sizeof__',
 '__str__',
 '__subclasshook__',
 'append',
 'clear',
 'copy',
 'count',
 'extend',
 'index',
 'insert',
 'pop',
 'remove',
 'reverse',
 'sort']

 dir (tuple)
 ['__add__',
 '__class__',
 '__class_getitem__',
 '__contains__',
 '__delattr__',
 '__dir__',
 '__doc__',
 '__eq__',
 '__format__',
 '__ge__',
 '__getattribute__',
 '__getitem__',
 '__getnewargs__',
 '__getstate__',
 '__gt__',
 '__hash__',
 '__init__',
 '__init_subclass__',
 '__iter__',
 '__le__',
 '__len__',
 '__lt__',
 '__mul__',
 '__ne__',
 '__new__',
 '__reduce__',
 '__reduce_ex__',
 '__repr__',
 '__rmul__',
 '__setattr__',
 '__sizeof__',
 '__str__',
 '__subclasshook__',
 'count',
 'index']

 dir (str)
 ['__add__',
 '__class__',
 '__contains__',
 '__delattr__',
 '__dir__',
 '__doc__',
 '__eq__',
 '__format__',
 '__ge__',
 '__getattribute__',
 '__getitem__',
 '__getnewargs__',
 '__getstate__',
 '__gt__',
 '__hash__',
 '__init__',
 '__init_subclass__',
 '__iter__',
 '__le__',
 '__len__',
 '__lt__',
 '__mod__',
 '__mul__',
 '__ne__',
 '__new__',
 '__reduce__',
 '__reduce_ex__',
 '__repr__',
 '__rmod__',
 '__rmul__',
 '__setattr__',
 '__sizeof__',
 '__str__',
 '__subclasshook__',
 'capitalize',
 'casefold',
 'center',
 'count',
 'encode',
 'endswith',
 'expandtabs',
 'find',
 'format',
 'format_map',
 'index',
 'isalnum',
 'isalpha',
 'isascii',
 'isdecimal',
 'isdigit',
 'isidentifier',
 'islower',
 'isnumeric',
 'isprintable',
 'isspace',
 'istitle',
 'isupper',
 'join',
 'ljust',
 'lower',
 'lstrip',
 'maketrans',
 'partition',
 'removeprefix',
 'removesuffix',
 'replace',
 'rfind',
 'rindex',
 'rjust',
 'rpartition',
 'rsplit',
 'rstrip',
 'split',
 'splitlines',
 'startswith',
 'strip',
 'swapcase',
 'title',
 'translate',
 'upper',
 'zfill']
 
 ### File Handling Function
 with open("chsl.txt", "r") as f:
  data =f.readlines()[0]
print(data)
https://youtu.be/O6glUoDcKR0?feature=shared current affairs

with open("sample.txt", "w") as f:
  f.write("Hello, world!")

with open("sample.txt", "r") as f:
  data =f.readlines()
print(data)

['Hello, world!']




 


## Custom Functions
