# Exp.no: 36
## HACKERRANK CHALLENGES-1

### AIM

To Write a Python Program to find Find the simple interest by getting the principal, rate and time value from the user.

### ALORITHM 

1. Start the program.

2. Read principal amount p (integer),time t in years (float),rate of interest r.

3. Define simpleInterest(p, t, r):
   a. If p >= 0, return (p * t * r) / 100.

4. Call the function simpleInterest(p, t, r).
   
5. Terminate the program.
   
### PROGRAM

```
def simpleInterest(p,t,r):
    if p>=0:
        return (p*t*r)/100
p=int(input())
t=float(input())
r=eval(input())
simpleInterest(p,t,r)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/b47bf137-8a75-410b-ad9e-ea9e3c92d34c)

### RESULT
Thus the python program was successfully implemented.
