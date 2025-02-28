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
eg:
with open("chsl.txt", "r") as f:
  data =f.readlines()[0]
print(data)
https://youtu.be/O6glUoDcKR0?feature=shared current affairs

eg:
with open("sample.txt", "w") as f:
  f.write("Hello, world!")

with open("sample.txt", "r") as f:
  data =f.readlines()
print(data)

['Hello, world!']


## Custom Functions
###Simple Function (No Parameters, No Return)
eg:
def greet():

  print('Hello world!')
greet()
output
Hello world!

### def and calling fns
eg:
def add_numbers():
  a = 10
  b = 20
  print("sum:", a+b)
add_numbers()
output
sum: 30

eg:
def welcome_message():
 print('Welcome to python functions!')
welcome_message()
output
Welcome to python functions!

eg:
def square_numbers():
  a = 10
  print("square:",a**2)
square_numbers()
output
square: 100

### function arguments
functions can take parameters to perform operations on inputs.
eg:
def add(a, b, c):
  print("sum:", a+b+c)
add(5, 3, 7)
output
sum: 15

eg:
def sub(a, b, c):
  print("sum:", a-b-c)
sub(5, 3, 7)
output
sum: -5

#key arguments and default arguments

eg:
def greet(name="Guest"):
  print(f"Hello, {name}!")
#greet()
greet("lavz")
output
Hello, lavz!

eg:
def greet(name="Guest"):
  print(f"Hello", name)
greet()
output
Hello Guest

eg:
def greet(name="Guest"):
  print(f"Hello", name)
greet("lavz")
output
Hello lavz

eg:
def multiply(a, b):
  print("multiple:", a*b)
multiply(5, 3)
output
multiple: 15

eg:
def multiply(a=1, b=1):
  print("multiple:", a*b)
multiply()
output
multiple: 1

### Retrun values
A function can return a value using the keyword
eg:
def add(a, b):
  return a+b
result = add(4, 6)
print("Result:", result)
output
Result: 10

eg:
def add(a, b):
  print( a+b)
result = add(4, 6)
print("Result:", result)
output
10
Result: None

eg:
def arithemetic(a, b):
  return a+b, a-b, a*b, a/b
result = arithemetic(10, 5)
print("Result:", result)
output
Result: (15, 5, 50, 2.0)

eg:
def arithemetic(a, b):
  return a+b, a-b, a*b, a/b
tsum, tdiff, tmul, tdiv = arithemetic(10, 5)
print(tsum, tdiff, tmul, tdiv)
output
15 5 50 2.0

### scope of variable
Local - variables exist inside a function
global - variables exist outside all functions
eg:
x = 10
def my_func():
 x=5
 print("Inside function", x)
my_func()
print("outside function", x)
output
Inside function 5
outside function 10

eg:
def add_num(a, b):
  """ this function adds two numbers """
  sum = a+b
  return sum
add_num(4, 6)
output
10

### Docstrings
eg:
print(add_num.__doc__)
output
 this function adds two numbers 

eg:
def print_args(*kwargs):
  for item in kwargs:
   print(item)
print_args("hi", "hello", "bye")
output
hi
hello
bye

eg:
def print_args(*kwargs):
  for item in kwargs:
   print(item)
print_args("hi", "how r u")
output
hi
how r u



