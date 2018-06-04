# Types Of Functions

### Built in Functions:
Eg:
id()
type()
input()
eval()

### User Defined Functions
Q. Write a function to find factorial of given number?
def fact(num):
result=1
while num>=1:
result=result*num
num=num-1
return result
for i in range(1,5):
print("The Factorial of",i,"is :",fact(i)) 

### Returning multiple values from a function:
def sum_sub(a,b):
 sum=a+b
 sub=a-b
 return sum,sub
 x,y=sum_sub(100,50)
 print("The Sum is :",x)
 print("The Subtraction is :",y)

Output
The Sum is : 150
The Subtraction is : 50 

### lambda Function:
lambda argument_list : expression
Q. Lambda Function to find biggest of given values.
s=lambda a,b:a if a>b else b
print("The Biggest of 10,20 is:",s(10,20))
print("The Biggest of 100,200 is:",s(100,200))
Output
The Biggest of 10,20 is: 20
The Biggest of 100,200 is: 200 

### filter() function:
We can use filter() function to filter values from the given sequence based on some
condition.
filter(function,sequence)
l=[0,5,10,15,20,25,30]
l1=list(filter(lambda x:x%2==0,l))
print(l1) #[0,10,20,30]
l2=list(filter(lambda x:x%2!=0,l))
print(l2) #[5,15,25] 

### map() function:
For every element present in the given sequence,apply some functionality and generate
new element with the required modification. For this requirement we should go for
map() function.
Ex.
l=[1,2,3,4,5]
def doubleIt(x):
return 2*x
l1=list(map(doubleIt,l))
print(l1) #[2, 4, 6, 8, 10] 

### reduce() function:
reduce() function reduces sequence of elements into a single element by applying the
specified function.

reduce(function,sequence)
Ex.
from functools import *
l=[10,20,30,40,50]
result=reduce(lambda x,y:x+y,l)

### Function Decorators:
To extent the funtionality of present function we can use decorator

def add(func):
    def inner():
        print('add')
        x=func()
        return x+x
    return inner
        
def mul(func):
    def inner():
        print('Mul')
        x=func()
        return x*x
    return inner    

@mul
@add
def number():
    return 10
 print(number())
print(result) # 150 



### Generators
- memory utilization 
- time utilization )

Ex.
n=int(input('Enter Number'))
def feb(n):
  a,b=1,1
  for i in range(n-1):
   a,b=b,a+b
  yield a
value=feb(n)
for i in value:
    print(i)
    
