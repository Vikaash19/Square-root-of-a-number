# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
~~~
#Program to find the square root for the given number(newton's method) using function
# Developed by: Vikaash K S
# Register number: 23013426
def sqrt():
    n=int(input())
    a=100
    x=0.5*n
    for i in range(a):
        r=0.5*(x+n/x)
        x=r
    print("Square root of the number:",r)
sqrt()
~~~
## Output:
![square root of a no](https://github.com/Vikaash19/Square-root-of-a-number/assets/148514589/e4080991-1dad-4d55-99cf-163af1aa75de)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
