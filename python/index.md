# Day 5 (08-05-2023)
> **Self Introduction in Python**
```
print ('Self Introduction\n')
n='Sooryanath G'
a=19
c='GPTC Chelakkara'
d='Computer Engineering'
p='Panjal'
print('My Name is',n,'\n',
'I am',a,'years old','\n',
'I am from',p,'\n',
'I am  Studying in',d,'department of',c,'\n')
```
## Sample Code With Output
![output](https://github.com/sooryanath1/Internship1/blob/main/img/Screenshot%202023-05-08%20111830.png)
> **Largest Among 3 Numbers**
```
'''

Largest Among 3 Numbers

'''
x=int(input("enter a number : "))
y=int(input("enter another number : "))
z=int(input("enter one more number : "))
if(x>y):
    if(x>z):
        print(x)
elif(y>x):
    if(y>z):
        print(y)
    else:
        print(z)
else:
    print('invalid')
```
![sample output](https://github.com/sooryanath1/Internship1/blob/main/img/largest3.png)
> **Calculator**
```
'''

calculator

'''
print("\n1.addition\n2.division\n3.multiplication\n4.substarction\n")
c=int(input("enter your choice "))
x=int(input("enter a number : "))
y=int(input("enter another number : "))
if(c==1):
    print('result : ',x+y)
elif(c==2):
    print('result : ',x/y)
elif(c==3):
    print('result : ',x*y)
elif(c==4):
    print('result : ',x-y)
else:
    print("inavlid choice")
```
![sampleoutput](https://github.com/sooryanath1/Internship1/blob/main/img/calc.png)
> **Vowels Check**
```
'''

Vowel

'''
x=str(input('enter a letter '))
if(x=='a'):
    print("vowel")
elif(x=='e'):
    print("vowel")
elif(x=='i'):
    print("vowel")
elif(x=='o'):
    print("vowel")
elif(x=='u'):
    print("vowel")
else:
    print('consonant')
```
![sampleoutput](https://github.com/sooryanath1/Internship1/blob/main/img/vowel2.png)
 # Day 6 (09-05-2023)
> **Odd & Even Using For Loop** 
```
'''

 Odd & Even Using For Loop
'''

'''

 Odd For Loop
'''

for i in range(1,11,2):
    print(i)

print('-------------')   
'''
Even For Loop
'''
for i in range(2,11,2):
    print(i)
```
![sampleoutput](https://github.com/sooryanath1/Internship1/blob/main/img/odd&even.png)
> **Multiplication Table Using For Loop** 
```
'''
Multiplication Table Using For Loop
 
'''
a=int(input("enter a number"))
for i in range(1,11,1):
    print(i ,'x',a,'=',a*i)
    
```
![sampleoutput](https://github.com/sooryanath1/Internship1/blob/main/img/Multiplication%20Table%20Using%20For%20Loop.png)
> **Fibonacci Series** 
```
n=int(input("Enter the Limit"))
i=0
n1=0
n2=1
n3=0
while(i<n):
    print(n3)
   
    
    n3=n3+n2
    n2=n1
    n1=n3
    i=i+1

```
![Fibonacci Seriess](https://user-images.githubusercontent.com/132330607/237016556-f70d23bf-b8c3-43a5-8194-8f0ee1b32c02.png)
> **Sum Of N numbers Using While Loop** 
```
n=int(input("Enter the Limit"))
i=1
s=0
while(i<=n):
   s+=i
   i=i+1
print(s)

```
![Sum Of N numbers Using While Loop](https://user-images.githubusercontent.com/132330607/237017956-399a8557-d00d-45cf-8ba5-8e6646e4f0da.png)
> **Calculator Using Function**
```
'''
Calculator using Function


'''
def add(a,b):
    return a+b
def sub(a,b):
    return a-b
def mul(a,b):
    return a*b
def div(a,b):
    return a//b
print("\n1.Addition\n2.Substarction\n3.Multliplication\n4.Division\n")
c=int(input("Enter your choice number: "))
a=int(input("Enter a number: "))
b=int(input("Enter another number: "))
if(c==1):
    w=add(a,b)
    print("The sum is",w)
elif(c==2):
    x=sub(a,b)
    print("The difference is",x)
elif(c==3):
    y=mul(a,b)
    print("The product is",y)
elif(c==4):
    z=div(a,b)
    print("The quotient is ",z)
else:
    print("invalid")

```
![Sum Using Function](https://user-images.githubusercontent.com/132330607/237047689-fc0c11e4-eeed-492e-89b5-9899f37423ba.png)
