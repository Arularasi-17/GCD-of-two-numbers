# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by:Arularasi U 
RegisterNumber:212223100002  
*/
```
def gcd():\
    num1,num2=int(input()),int(input())\
    if num1<num2:\
        smaller=num1\
    else:\
        smaller=num2\
    for i in range(1,smaller+1):\
        if num1%i==0 and num2%i==0:\
            gcd1=i\
    print("GCD of two numbers is:",gcd1)\

## Output:
![alt text](<Screenshot 2024-04-16 200317.png>)
![alt text](<Screenshot 2024-04-16 200329.png>)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
