# Python cours 
Python dia language de programation.

Python dia afaka anaovana zavatra maro toy ny site web,Application,Logicil,Jeux video ,etc.
# Parcours tokony arahina raha anomboka python
- Syntax
- Comments
- Variables
- Data Types
- Booleans
- Operators
- Dictionaries
- Condition if else
- Boucle
- Functions
- Arrays
- Modules
- Dates
- User Input

## Syntax
### Fijerena resulat ny code python.
```py
print("Hello, World!")
```

## Comments
```py
# this is comment
print("Hello, World!")
```

## Variables
Karazan fampiasana varable
```py
MyName='Rakotonirina'
My_Name='Rakotonirina'
```
Ou
```py
Name, age = 'Rakoto',19
```

## Data Types
```py
    x = str("Hello World")	#str	
    x = int(20)	#int	
    x = float(20.5)	#float	
    x = complex(1j)	#complex	
    x = list(("apple", "banana", "cherry"))#list	
    x = tuple(("apple", "banana", "cherry"))	#tuple	
    x = range(6)	#range	
```
## Python Numbers
```py
x = 1    # int
y = 2.8  # float
z = 1j   # complex
print(type(x))
```

## Booleans
```py
x=True
y=False
```
## Operators
```py
 +	Addition	x + y	
 -	Subtraction	x - y	
 *	Multiplication	x * y	
 /	Division	x / y	
 %	Modulus	x % y	
**	Exponentiation	x ** y	
```
## Dictionaries
```py
thislist = ["apple", "banana", "cherry"]
thistuple = ("apple", "banana", "cherry")
thisset = {"apple", "banana", "cherry"}
```
## Condition if else
```py
if b > a :
  print("b lehibe noho ny a")
  elif a == b:
    print("a sy b dia mitovy")
else:
  print("b dia kely nohony a")

```
## Boucle
```py
 #while loops
        i = 1
        while i < 6:
        print(i)
        i += 1
    # break_statment
    break 
    # continue Statement
    continue

    # loops
    # Python For Loops
    fruits = ["apple", "banana", "cherry"]
        for x in fruits:
        print(x)
    # Looping Through a String
        for x in "banana":
            print(x)
    # break statmentt
    fruits = ["apple", "banana", "cherry"]
        for x in fruits:
        print(x)
        if x == "banana":
            break
    # range
    for x in range(6):
        print(x)
    for x in range(2, 6):
        print(x)
    for x in range(2, 30, 3):
        print(x)

```
## Functions
```py
def my_function():
  print("Bonjour")

my_function()#call funtion

#argument + parametre
def my_function(fname):
    print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")

    # liste argument
def my_function(food):
    for x in food:
        print(x)

fruits = ["apple", "banana", "cherry"]

my_function(fruits)

```