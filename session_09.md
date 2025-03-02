# Object Oriented Programming (OOP)
In Python, OOP (Object-Oriented Programming) is a programming paradigm that uses objects and classes to structure and organize code. It focuses on creating reusable, modular, and efficient code by modeling real-world entities as objects with attributes (data) and methods (functions).

## Class
1. A blueprint or template for creating objects.
2. Defines the attributes (data) and methods (functions) that the objects will have.

### Basic Class Definition
#### Constructor (__init__):
1. A special method called when an object is created.
2. Used to initialize instance attributes.
3. The self parameter refers to the instance of the class.

Eg:
class person:
  def __init__(self, name, id): #constructor
    self.name = name
    self.age = id
  def sayHello(self):
    print("Hello! My name is "+ self.name)
p1 = person("Dan", 1234)
p1.sayHello()
Output
Hello! My name is Dan

### Class Attibutes
1. Variables that belong to an object or class.
2. Represent the state or data of the object.
   
### Class Functions
1. Functions that belong to an object or class.
2. Define the behavior of the object.
   
## Object
1. An instance of a class.
2. Created using the class blueprint.

### Creating objects of a particular class
eg 1:
class Dog:
  def __init__(self, name, age):
    self.name = name
    self.age = age
my_pet = Dog("bob", 5)
print(my_pet.name)
print(my_pet.age)

my_pet1 = Dog("dobby", 3)
print(my_pet1.name)
print(my_pet1.age)

output
bob
5
dobby
3

eg2:
class Dog:
  def __init__(self, name, age, sound):
    self.name = name
    self.age = age
    self.sound = sound
  def say(self):
    print(self.sound)
my_pet = Dog("Bob", 5, "woof!...")
my_pet.say()
my_pet1 = Dog("dobby", 3, "Meww!...")
my_pet1.say()

output
woof!...
Meww!...

eg3:
class Dog:
  def __init__(self, name, age, sound):
    self.name = name
    self.age = age
    self.sound = sound
  def say(self):
    print(self.sound*2)
my_pet = Dog("Bob", 5, "woof!...")
my_pet.say()
my_pet1 = Dog("dobby", 3, "Meww!...")
my_pet1.say()

output
woof!...woof!...
Meww!...Meww!...

### Encapsulation:
1. Bundling data (attributes) and methods that operate on the data into a single unit (class).
2. Restricting direct access to some of an object's components (using private/protected attributes).

### Inheritance
1. A mechanism where a new class (child class) derives properties and behaviors from an existing class (parent class).
2. Promotes code reuse.

eg1 :
class Animal:
  def __init__(self, name, age, sound):
    self.name = name
    self.age = age
    self.sound = sound
  def say(self):
    print(self.sound)

class Dog(Animal):
  def __init__(self, name, age, sound):
    super().__init__(name, age, sound)
  def action(self):
   print("Moves tails")

class Cat(Animal):
  def __init__(self, name, age, sound):
    super().__init__(name, age, sound)
  def action(self):
   print("Moves tails")
Pet1=Dog("Alphu", 2, "Bow")
Pet1.action()
Pet1.say()
print(Pet1.name)
print(Pet1.age)

output
Moves tails
Bow
Alphu
2

Pet2=Cat("Beta", 4, "Meaw")
Pet2.action()
Pet2.say()
print(Pet2.name)
print(Pet2.age)

output
Moves tails
Meaw
Beta
4

eg2:
class Calculator:
  def __init__(self, x, y):
    self.x = x
    self.y = y
  def add(self):
    print("sum", self.x + self.y)

  def sub(self):
    print("difference", self.x - self.y)

  def multiply(self):
    print("multiplication", self.x * self.y)

  def div(self):
    print("division", self.x / self.y)
    result = Calculator(4, 3)
result.add()
result.sub()
result.multiply()
result.div()

output
sum 7
difference 1
multiplication 12
division 1.3333333333333333


### Polymorphism:
1. The ability of different classes to be treated as instances of the same class through a common interface.
   
### Abstraction:
1. Hiding complex implementation details and exposing only the necessary features.
2. Achieved using abstract classes or interfaces.

eg:
from os import listdir
from os.path import join, getsize

file_path = join("C:\\", "Users", "ACER", "Downloads")
file_names = listdir(file_path)
print(file_names)

for i in file_names: #to filter the pdf files from the path
    if ".pdf" in i:
        print(i)
max_size = 0
for file_name in file_names:

    file_size = getsize(join("C:\\", "Users", "ACER", "Downloads", file_name)) #to get the largest file
    if file_size > max_size:
        max_size = file_size
        print(file_name, "contains", file_size, "KBs")

print(max_size)

output
1688631932 (1).pdf
1688631932.pdf
1701494159850clvDNsUhKH2WXOnA.pdf
1996163_ReleaseLetter_1 (1).pdf
1996163_ReleaseLetter_1.pdf
1996163_ServiceCertificate_1 (1).pdf
1996163_ServiceCertificate_1 (2).pdf
1996163_ServiceCertificate_1 (3) (1).pdf
1996163_ServiceCertificate_1 (3).pdf
1996163_ServiceCertificate_1.pdf
a-b-c-can-do-a-particular-job-in-18-45-10-hour--602d4709a1ed6e9ed5496d2c.pdf
Aadharcard copy.pdf
abhijith CV.pdf
abhijith CV1.pdf
acknowledgementSlip_S1855669673000.pdf
Admit Card.pdf
application (1).pdf
application.pdf
Arihant Banking Awareness [Old Edition].pdf
Artifact 5 PF Withdrawal Form_Ver 0.4 (1).pdf
Artifact 5 PF Withdrawal Form_Ver 0.4.pdf
Aswin_Sunil.pdf
Banking Ombudsman_ Meaning & Imp. Rules for Filing Complaints.pdf
BIOLOGY.pdf
Capital Market in India_Meaning,Functions,Capital vs Money Market.pdf
Certified Specialist in Data Science and Analytics-First Installment .pdf
chsl.pdf
Computer Assistant Grade II - Govt. Sectt.KPSC-2016Feb@PSC WINNERS (1).pdf
Computer Assistant Grade II - Govt. Sectt.KPSC-2016Feb@PSC WINNERS.pdf
COMPUTER OPERATOR - KIRTADS-2015 july@PSC WINNERS.pdf
COMPUTER OPERATOR-2016Feb@PSC WINNERS.pdf
Computer Programmer-cum-Operator - Kerala State Beverages (Manufacturing &.pdf
Cross-selling vs Up-selling in Bank, Meaning, Uses, Advantages.pdf
Data Entry Operator 2014.pdf
ENGLISH_VOCAB_CHECKLIST_21_BY_NIMISHA_MAM_15TH_JUNE_2024_docx.pdf
Form8_S11134O8W2403241200017.pdf.pdf
Form8_S11134O8W2503241200000.pdf.pdf
Geography Notes for SSC CGL PDF - Download Free PDF!.pdf
History Notes for SSC CGL - Download Complete Ancient, Medieval & Modern History Notes for SSC Exams PDF!.pdf
INFORMATION TECHNOLOGY & CYBERLAW.pdf
jan.pdf
JUNIOR INSTRUCTOR COMPUTER OPERATOR AND PROGRAMMING ASSISTANT -2019July@PSC WINNERS.pdf
JUNIOR INSTRUCTOR COMPUTER OPERATOR AND PROGRAMMING ASSISTANT-2012@PSC WINNERS.pdf
Khadi Board LDC Stage 4.pdf
LDC 2024 Prelims.pdf
LDC Main Questions Paper 2021 .pdf
mcq-on-biology--5eea6a0c39140f30f369e02a.pdf
mcq-on-delhi-sultanate--5eea6a1239140f30f369ec17.pdf
mcq-on-indian-geography--5eea6a1239140f30f369ec90.pdf
mcq-on-mughal-empire--5eea6a1239140f30f369ec1d.pdf
mcq-on-viceroy-and-governor--5eea6a1239140f30f369ecf2.pdf
Nitin K R - Resume.pdf
Nitin K R Resume-pdf (1).pdf
Nitin K R Resume-pdf.pdf
Not_0052024_0672024.pdf
Not_0152023_5212023.pdf
Not_0172024_7242024.pdf
Nov_2023.pdf
PFSettlementLetter1996163.pdf
PFWithdrawalApplication.pdf
PFWithdrawalGuidelines.pdf
PF_1996163(20232024) (1).pdf
PF_1996163(20232024) (2).pdf
PF_1996163(20232024).pdf
PROGRAMMER - KPSC-2015 AUGUST@PSC WINNERS.pdf
PSC COMPUTER PROGRAMMER-CUM-OPERATOR - KERALA STATE BEVERAGES - MANUFACTURING AND MARKETING CORPORATION LTD-2014- PSC WINNERS.pdf
rb.pdf
RBI-ASSISTANT-2020-MEMORY-BASED-Questions.pdf
RBI-ASSISTANT-2020-MEMORY-BASED-Solutions.pdf
RBI-Assistant-PYP-1-Question-Paper-1.pdf
RBI-Assistant-PYP-2-Question-Paper-1.pdf
Resume_Lavanya (10).pdf
Resume_Lavanya (11).pdf
Resume_Lavanya (12).pdf
Resume_Lavanya (2).pdf
Resume_Lavanya (3).pdf
Resume_Lavanya (4).pdf
Resume_Lavanya (5).pdf
Resume_Lavanya (6).pdf
Resume_Lavanya (7).pdf
Resume_Lavanya (8).pdf
Resume_Lavanya (9).pdf
Resume_Lavanya.pdf
Scanned_20240914-1212.pdf
ssc cgl.pdf
ssc.p.pdf
ssc.pdf
System Administrator- Programmer- System Analyst- Computer Programmer 2022 October@PSC WINNERS.pdf
SYSTEM ANALYST -PROGRAMMER - KPSC-2019May@PSC WINNERS.pdf
System Analyst -Programmer-2019October@PSC WINNERS.pdf
thasleem -CV.pdf
thasleem cv 1 (1).pdf
thasleem cv 1.pdf
thasleem cv.pdf
thasleem_CV.pdf
The-Hindu-Review-November-2023.pdf
Untitled.pdf
__ BillDesk Payment Gateway __.pdf
02 - Copy.jpg contains 17237 KBs
02.jpg contains 19526 KBs
1688631932 (1).pdf contains 1532811 KBs
1688631932.pdf contains 1608983 KBs
1T6A8573 (1).JPG contains 6755098 KBs
Arihant Banking Awareness [Old Edition].pdf contains 82739175 KBs
VSCodeUserSetup-x64-1.97.2.exe contains 105639336 KBs
105639336
