# EXP - 5 Find the square root of a number 
# DATE : 04/09/24
## AIM :
To write a program to find the square root of a number.

## Equipments Required :
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm :
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program :
```

Program to find the square root for the given number(newton's method) using function.
Developed by: Aankarsh J
RegisterNumber: 22304386

```
```
def squareroot(num1,iternum):
    num2=float(num1)
    for i in range(100):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)
num1=int(input())
iternum=100
squareroot(num1,iternum)
```

## Output :
![Ex - 5 (Image)](https://github.com/user-attachments/assets/8bfcaa2e-9f9f-4624-8f86-f5ae0ffa35fc)


## Result :
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
