## Hello all Wellcome to Python World!!
Lets discuss about If... Else...
Python Conditions and If statements Python supports the usual logical conditions from mathematics:

Equals: a == b

Not Equals: a != b

Less than: a < b

Less than or equal to: a <= b

Greater than: a > b

Greater than or equal to: a >= b

These conditions can be used in several ways, most commonly in "if statements" and loops.

An "if statement" is written by using the if keyword. The syntax of the if statement is:

if test_condition: statement(s)


```python
a=33
b=200
if b>a:
    print("b is greater than a")
```

    b is greater than a


If test_condition is True, the body of the if statement is executed.

However, if test_condition is False, the body of the if statement is skipped from execution.


```python
a=10
b=5

if a>b:
    print("a is greater than b")
```

    a is greater than b


### elif
The elif keyword catches anything which isn't caught by the preceding conditions.


```python
a=33
b=200
if a>b:
    print('a is greater than b')
elif b>a:
    print('b is greater than a')
else:
    print('a is greater than b')
```

    b is greater than a


In this example a is greater than b, so the first condition is not true, also the elif condition is not true, so we go to the else condition and print to screen that "a is greater than b".

Here we will get the correct answer 'b is greater than a'

## Short Hand If



```python
print('a is greater than b')
```

    a is greater than b



```python
a=33
b=200
if b>a:
    print("b is greater than a")
```

    b is greater than a



```python
if b>a: print("b is greater than a")
```

    b is greater than a



```python
a = 200
b = 300
```


```python
print ('a is greater than b') if a>b else print('b is greater than a')
```

    b is greater than a


## And
The and keyword is a logical operator, and is used to combine conditional statements:


```python
a = 200
b = 33
c = 500
if a > b and c > a:
    print("Both conditions are True")
```

    Both conditions are True


## Or
The or keyword is a logical operator, and is used to combine conditional statements:


```python
a = 200
b = 33
c = 500
if a > b or a > c:
      print("At least one of the conditions is True")
```

    At least one of the conditions is True


## Nested If
You can have if statements inside if statements, this is called nested if statements.


```python
x = 41

if x > 10:
    print("Above ten,")
    if x > 20:
        print("and also above 20!")
    else:
        print("but not above 20.")
```

    Above ten,
    and also above 20!


Here first inside satement will execute then outside statement will execute 

## The pass Statement
if statements cannot be empty, but if you for some reason have an if statement with no content, put in the pass statement to avoid getting an error.


```python
a = 33
b = 200

if b > a:
    pass
```


```python
a=23
b=45
if a<b:
    print("b is greater than a") 
```

    b is greater than a


## Programming Task
Can you create a program to check whether a number is positive or negative or 0?

To create this program, create a variable named number and assign a float value to it based on the user input. Then using a if statement, check if the number variable is positive or negative or 0.

If number is positive, print "The number is positive"
If number is 0, print "The number is 0"
If number is negative, print "The number is negativ


```python
number=int(input("enter a nuber:"))
if number>0:
    print("possitive")
elif number==0:
    print("zero")
else:
    print("negative")
```


```python

```
