### 1.  In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.


```python
*
Expression as it is mathematical operator

'hello'
Value as it is string

-87.8
Value as it is integer(float)

-
Expression as it is mathematical operator

/
Expressionas it is mathematical operator

+
Expression as it is mathematical operator

6
Value as it is integer
```

### 2. What is the difference between string and variable?


```python
String means any value that can be aplhabet or sequence of aplhabet or infact numeric which written inside quotes '' or double quotes "" .

# String means any value that can be aplhabet or sequence of aplhabet or infact numeric which written inside quotes '' or double quotes "" .

# varible means a storage box which contains our   data   and this data can be anything .And if we give any name to our varible than it called varible name as we all have some na # lets understand by a example

Name= "XYZ" # Name (is varible name) is varible which contain string called "XYZ"

Class="10"    # Class (is varible name) is varible which contain string called "10" as string can be anything written inside quotes"" or ''

print(Name ," ", Class)
```

### 3. Describe three different data types. 


```python
Present=True # Boolean datatype represent only two value True(1) or False(0)

Class= 10 #integer datatype is a numeric whole no. value that can be positive por negative but without decimal

Id =10+5j #complex type made with real + imaginary no. (10+10j)

print(type(Present))

print(type(Class))

print(type(Id))

<class 'bool'>

<class 'int'>

<class 'complex'>
```

### 4.  What is an expression made up of? What do all expressions do?


```python
Expression is made up of different numbers, varibles, and opertors and its use PEDMAS Rule.(Parenthesis Exponents Division Multiplication Addition Subtraction)

like R=[(a/10)*((a+b)+(b-5)+a)]

And all expressions evaluate into a single value i.e R in above expression

a,b=20,10 R=[(a/10)*((a+b)+(b-5)+a)]

print(a/10) #20/10=2

print(a+b) #20+10=30

print(b-5) #10-5=5

print((a+b)+(b-5)+a) #30+5+20=55

print([(a/10)*((a+b)+(b-5)+a)]) print("************************************************************************") print("Expreesion value =",R)

type(R) # List as it is enclosed with []

2.0

30

5

55

[110.0]

************************************************************************

Expreesion value = [110.0]

 list
```

### 5.  This assignment statements, like spam = 10. What is the difference between an expression and a statement?


```python
Expression is made with value, varible and opertors which evaluated and make a single value like in above example R=[(a/10)*((a+b)+(b-5)+a)] where expression evaluate into single value tht is R (110)

but Statement does not evaluate like R=110 as 110 is assign to R but in above example expression evaluate and give R value as 110
```

### 6.  After running the following code, what does the variable bacon contain?


```python
bacon = 22

bacon+1

bacon = 22 # 22 assign to bacon

bacon + 1 #22+1=23

23
```

### 7.  What should the values of the following two terms be? 'spam' + 'spamspam'      'spam' * 3


```python
print('spam' + 'spamspam') # both perfrom concatenation and give same result

print('spam' * 3)

spamspamspam

spamspamspam
```

### 8.  Why is eggs a valid variable name while 100 is invalid?


```python
Because giving varible name it have some rules which we have to follow like<br> 1.varible can only start with string or it can be follow by underscore(_) like _eggs

2. can't start with number but it can be follow by string like eggs100

3. can't be a keyword like while , for , is , True,print,else or etc

4. can't contains symbol like @,#,%,$ , but can contain _

5.no space between varible for space purpose we can use _ like eggs_100

#valid varible name

eggs=10

_eggs=10

eggs_100=10

eggs100=10

# not valid name

eggs@10=10 # no symbols

100=10 #no number

while=100 # keywords we can see color also if it black than only valid if it dark green means it keyword
```

### 9.  What three functions can be used to get the integer, floating-point number, or string version of a value?


```python
int() for integer

float()forfloating-pointnumber

str()forstring

A="100"

print("********************************Integer***************************")

B=int(A)

print("Integer is ",B)

print(type(B))

print("********************************Floating-point number***************************") A=float(B)

print("Floating-point number is ",A)

print(type(A))

print("********************************STRING***************************")

B=str(A)

print("String is ",B)

print(type(B))

********************************Integer***************************

Integer is 100

<class 'int'>

********************************Floating-point number***************************

Floating-point number is 100.0

<class 'float'>

********************************STRING***************************

String is 100.0

<class 'str'>
```

### 10.     Why does this expression cause an error? How can you fix it? 'I have eaten ' + 99 + ' burritos.'


```python
It cause error because we can't concatenate string with integer for that we need to typecaste integer into string by str()

print('I have eaten ' + str(99) + ' burritos')

I have eaten 99 burritos

My Github link:

https://github.com/PoojaDasIndia/Assignment_Python/blob/main/Python%20Basic%20Assignments/Python_Basic_Assignment_1%20.ipynb
```
