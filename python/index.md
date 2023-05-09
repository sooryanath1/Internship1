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
![sampleoutput](https://github.com/sooryanath1/Internship1/blob/main/img/Multiplication Table Using For Loop.png)
