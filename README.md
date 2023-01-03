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
```python

Developed by: JENISHA.J
RegisterNumber:  22002972

a=int(input())
b=int(input())
def gcd():
    if a<b:
        smaller=a
    else:
        smaller=b
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)

```

## Output:
![gcd of two number](gcd.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
