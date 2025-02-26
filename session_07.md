# Control Flow
## Conditional
Conditional statements allow us to execute different blocks of code based on a condition.
eg:
eg:
x = 10
if x>5:
      print("x is greater than 5")
output
x is greater than 5

### IF
This check a condition, and iff its true, the intended code block under it will be executed.
eg:
x =4
if x>5:
  print("x is greater than 5")
else:
    print("x is not greater than 5")
print("x contains:", x)
output
x is not greater than 5
x contains 4

### IF-ELSE
This captures any rremaining cases that don't match, the if or elif conditions. It executes if all previous conditions are false.
eg:
x = 7
if x>5:
  print("x is greater than 5")
  print(list(range(x)))
else:
    print("x is not greater than 5")
output
x is greater than 5
[0, 1, 2, 3, 4, 5, 6]

eg:
x = 10
if x>10:
  print("x is greater than 10")
elif x==10:
    print("x is exactly 10")
output
x is exactly 10

### IF-ELIF-ELSE
This will check multiple conditions. If the if condition is False, it checks the elif condition.
eg:
x = 5
if x>0:
 print("x is positive number")
elif x<0:
 print("x is negative number")
else:
 print("x is zero")
output
x is positive number

eg:
x = -1
if x>0:
 print("x is positive number")
elif x<0:
 print("x is negative number")
else:
 print("x is zero")
output
x is negative number

eg:
x = 0
if x>0:
 print("x is positive number")
elif x<0:
 print("x is negative number")
else:
 print("x is zero")
output
x is zero

### Nested IFs
eg:
x = 15
if x>10:
 print("x is greater than 10")
 if x>20:
  print("x is also greater than 20")
 else:
  print("x is not greater than 20")
output
x is greater than 10
x is not greater than 20

QS 1:
numdict ={1:"one", 2:"two", 3:"three", 4:"four", 5:"five", 6:"six", 7:"seven", 8:"eight", 9:"nine"}
a= input("enter a number:")
for numdicts in a:
     print(numdict[int(numdicts)], end=" ")
output
enter a number:9342
nine three four two 

QS 2:
x = "141"
a=list(x)
b=a[::-1]
if a==b:
 print(x,"is pallindrome")
else:
  print(x,"is not pallindrome")
output
141 is pallindrome

QS 3:
x = int(input("ënter a number"))
if x%2==0:
  if x%4==0:
    print(x,"is divisible by 4")
  else:
    print(x,"is not divisible by 4")
elif x%2!=0:
  if x%9==0:
    print(x, "is divisible by 9")
  else:
    print(x, "is not divisible by 9")
output
ënter a number15
15 is not divisible by 9

## Loops
Loops allow us to repeat a block of code multiple times.
### For Loop
A for loop is used for iterating over a sequence.we can execute a set of statements, once for each item in a list, tuple, set etc.
eg:
word = "data science"
for char in word:
  print (char)
output
d
a
t
a

s
c
i
e
n
c
e

eg:
word = "data science"
for char in word[::-1]:
  print (char)
output
e
c
n
e
i
c
s
 
a
t
a
d

eg:
for i in range(1,10,3):
 print(i)
output
1
4
7

### While Loop
while loop can execute a set of statements as long as a condition is true.
eg:
n = 1
while n<10:
  print(n)
  n = n+1
output
1
2
3
4
5
6
7
8
9

### Continue
With the continue statement we can stop the current iteration, and continue with the next.
eg:
numbers =[1, 2, 3, 4, 5]
for i in numbers:
  if i == 3:
    continue
  print(i)
print("outside of for loop")
output
1
2
4
5
outside of for loop
### Break
With the break statement we can stop the loop even if the while condition is true.
eg:
numbers =[1, 2, 3, 4, 5]
for i in numbers:
  if i == 3:
    break
  print(i)
print("outside of for loop")
output
1
2
outside of for loop
## Basic Library Usage
### Keyword library
It will allows us to interact with the list of reserved keywords in Python.
eg:
import keyword
print(keyword.kwlist)
len(keyword.kwlist)
output
['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
35

## Print formatting
eg:
a = 10
b = 20
print(a, b)
print("a =", a)
print("b =" , b)
print("a = {} and b = {}". format(a, b))
print("a = {0} and b = {1}". format(a, b))
print("a = {1} and b = {0}". format(a, b))
print("Hello {}, welcome to DSA Class". format(name))
print("{y} is {x}, years old". format(x= age, y=name))
output
10 20
a = 10
b = 20
a = 10 and b = 20
a = 10 and b = 20
a = 20 and b = 10
Hello Bob, welcome to DSA Class
Bob is 23, years old

## Placeholder passing
eg:
print("{} is {} years old". format(name, age))
output
Bob is 23 years old

eg:
print("{} is {} years old".format(age, name))
output
23 is Bob years old

eg:
print("{x} is {y} years old".format(y=age, x=name))
output
Bob is 23 years old

## Multiline Assignment
eg:
"""this is a
multiline
comment"""
output
'this is a \multiline\comment'

eg:
1+2+3+4+5+6
1+2+3+\
4+5\
+6
output
21

## Line-breaking
eg:
"Hello "*3
output
'Hello Hello Hello'

eg:
x  = 10
for x in range(1, x+1):
  print("*"*x)
output
*
**
***
****
*****
******
*******
********
*********
**********

eg:
for x in range(1, 6):
  print("*"*x)
output
*
**
***
****
*****

eg:
a = int(input("enter a number"))
for x in range(1, x+1):
 print("*"*x)
output
enter a number2
*
**
***

eg:
a = int(input("enter a number"))
for x in range(1, a, 2):
 nsp = (a-x)//2
 print(" "*nsp + "*"*x + ""*nsp)
output
enter a number20
         *
        ***
       *****
      *******
     *********
    ***********
   *************
  ***************
 *****************
*******************

eg:
a = int(input("enter a number"))
for x in range(1, a, 1):
 nsp = (a-x)//1
 print(" "*nsp + "*"*x + ""*nsp)
output
enter a number7
      *
     **
    ***
   ****
  *****
 ******
