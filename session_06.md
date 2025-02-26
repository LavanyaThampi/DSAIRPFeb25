# Installations

1. [Python download link](https://www.python.org/downloads/)
2. [Visual Studio download link](https://code.visualstudio.com/download)
3. [Git bash installation link](https://git-scm.com/downloads) (Mac and Linux users can skip this step)
4. Visual Studio Code Extensions:
    - Jupyter (Microsoft)
    - Andromeda (Eliver Lara)
    - Black Formatter (Microsoft)
    - Flake8 (Microsoft)

## Checklist
1. Git bash terminal access in VS Code
2. Venv creation. 
```bash 
pip install jupyter
```
3. Jupyter notebook
```bash
jupyter notebook
```
4. Auto code correction

# Python Data Types
## Numeric Type
### Integer
Represents integer numbers(whole numbers)
eg:
year = 2025
print(year)
output
2025

### Float
Represents decimal number
eg:-
bank_interest = 7.5
print(bank_interest)
output
7.5

### Complex
Represents complex numbers, which consists of real and imaginary.
eg:
c=3+8j
print(c)
outpput
3+8j

## Text Type
### String
Represents a string which is sequential characters
eg:-
Ïnstitute = "ICT"
print (Institute)
output
ICT

## Sequence Type
### List
Represnets a mutable sequence of elements(ordered collections)
eg 1:
digits = [0, 1, 2, 3]
len(digits)
output
4
eg 2).:
grocery = ["Apple", 5, "Orange"]
grocery[2]
output
Orange
eg 3) :
grocery[-1]
output
Orange
eg 4).:
grocery[-2]
output
5
eg 5):
grocery[0]
output
Apple

### Tuple
Represents immutable sequence of elements
eg:
my_tuple = (1, 2, 3)
my_tuple
output
1, 2, 3

### Range
Represents immutable sequence of numbers used in loops.
eg:
list(range(5))
output
[0, 1, 2, 3, 4]
eg:
list(range(1,10,2))
output
[1, 3, 5, 7, 9]
eg
list(range(10,1,-2)
output
[10, 8, 6, 4, 2]
eg:
list(range(11,1,-2)
output
[11, 9, 7, 5, 3]

## Mapping Type
### Dictionary
Represents a dictionary, which is an unordered collection of key-value pairs.
eg
data = {
    "Ïnstitute": "ICT" ,
    "City": "Trivandrum"
}
data["City"]
output
'Trivandrum'
eg:
data["State"] = "Kerala"
print(data)
output
{'Ïnstitute': 'ICT', 'City': 'Trivandrum', 'State': 'Kerala'}
eg:
data.keys()
output
dict_keys(['Ïnstitute', 'City', 'State'])
eg:
data.values()
output
dict_values(['ICT', 'Trivandrum', 'Kerala'])

## Set Type
Represents an unordered collection of unique elements.
eg:
my_set = {1, 1, 2, 3, 4}
print(my_set)
output
{1, 2, 3, 4}

## Boolean
Represents a Boolean value, which can either be True or False.
eg:
is_sunny = True
is_raining = False

print(is_sunny)
print(is_raining)
output
True
False
eg:
print(10>20)
Output
False
eg:
3. ==3.0
output
True
eg:
10.001 == 10.002
output
False

## None Type
Represents the absence of a value or a null value.
eg:
status = None
print(status)
output
None
eg:
0 == None
output
False
eg:
0 == False
output
True
eg:
None == False
output
False
eg:
-1 == True
output
False


# Operators in Python
## Arithmetic Operators
###Addition
###Subtraction
###Multiplication
###Division
###Modulous
###Exponent
###Floor Division
###Assignment Operator
##Comparison Operator
###>
###<
###>=
###<=
###==
###!=
##Logical Operators
###AND
###OR
###NOT
###Membership Operator
###IN
###NOT IN
###Identity Operator
###is
###is not
