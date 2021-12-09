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
def gcd():
    if num1>num2:
        smaller=num2
    else:
        smaller=num1
    for i in range(1,smaller+1):
        if (num1%i==0 and num2%i==0):
            a=i
    print('GCD of two numbers is:',a)
```

## Output:
![gcd of two number](output.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
