## NAME : SAJITH AHAMED F
## REG NO: 212223240144
## DATE : 23/03/2024

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
```PYTHON
DEVELOPED BY:SAJITH AHAMED F
REG NO: 212223240144

def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller = n2
    else:
        smaller = n1
    for i in range (1,smaller+1):
        if(n1%i==0 and n2%i==0):
           hcf=i
    print("GCD of two numbers is:",hcf)
```


## Output:

![Screenshot 2024-04-08 234054](https://github.com/Sajith-28/GCD-of-two-numbers/assets/149937471/49ff80bb-f1aa-4708-bc3f-33aed8348372)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
