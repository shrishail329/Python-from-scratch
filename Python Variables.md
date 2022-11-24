### Hello Guys!! Let's Rock the Jupyter NoteBook

##### We will discuss about the Python Variables 

Variables are containers for storing data values.

Python has no command for declaring a variable.

A variable is created the moment you first assign a value to it.

Variables do not need to be declared with any particular type, and can even change type after they have been set.

Variable Names

A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume).

Rules for Python variables:
A variable name must start with a letter or the underscore character

A variable name cannot start with a number

A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )

Variable names are case-sensitive (age, Age and AGE are three different variables)


```python
age = 32
print(age)
```

    32



```python
Age = 35
print(Age)
```

    35



```python
15age = 35
```


      Cell In [4], line 1
        15age = 35
         ^
    SyntaxError: invalid decimal literal




```python
name2 = 'shrishail'
```


```python
AGE = 65
```


```python
AGE
```




    65




```python
Age
```




    35




```python
age
```




    32




```python
my_name = 'shrishail'
my_name
```




    'shrishail'




```python
_my_name = 'shrishail'
_my_name
```




    'shrishail'




```python
my name = 'shrishail'
```


      Cell In [13], line 1
        my name = 'shrishail'
           ^
    SyntaxError: invalid syntax



"Remember that variable names are case-sensitive"

Multi Words Variable Names

Variable names with more than one word can be difficult to read.

There are several techniques you can use to make them more readable:

### Camel Case
Each word, except the first, starts with a capital letter:


```python
MyNameIs = 'SHRISHAIL'
```

#### Pascal Case


```python
MyNameIs = 'shrishail'
```

#### Snake Case


```python
my_name_is = 'shrishail'
```

#### Many Values to Multiple Variables


```python
x, y, z = 'shree', 'manju', 'ravi'
x
```




    'shree'




```python
y
```




    'manju'




```python
z
```




    'ravi'




```python
type(x)
```




    str




```python
#One Value to Multiple Variables
x=y=z='Mango'
```


```python
x
```




    'Mango'




```python
y
```




    'Mango'




```python
z
```




    'Mango'



###### Unpack a Collection

If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables. This is called unpacking.




```python
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
```


```python
x
```




    'apple'




```python
y
```




    'banana'




```python
z
```




    'cherry'




```python
fruits
```




    ['apple', 'banana', 'cherry']




```python
fruits[1]
```




    'banana'




```python
fruits[0]
```




    'apple'




```python
fruits[2]
```




    'cherry'



## Global Variables
Variables that are created outside of a function (as in all of the examples above) are known as global variables.

Global variables can be used by everyone, both inside of functions and outside.


```python
x = 'Assam'
def my_fun():
    print('i studied in '+x+' university')
my_fun()
```

    i studied in Assam university



```python
 # local variable

def myfun():
    x='GKVK'
    print('my clg name is '+ x)
    
myfun()
```


```python
# local variable 
def myfun():
    x = 'Extension'
    print('my department was ' +x)
myfun()
```

    my department was Extension

