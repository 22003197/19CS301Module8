# Exp.no: 39
## HACKERRANK-4

### AIM

To write python program to find the sum of all digits in a number.

### ALORITHM 

1. Start the program.

2. Read an integer n.

3. Initialize total as 0.

4. While n > 0:
   a. Add the last digit to total.
   b. Remove the last digit.

5. Print total.

6. Terminate the program.
   
### PROGRAM

```
n=int(input())
tot=0
while n>0:
    tot += n%10
    n //= 10
print(tot)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/385c694a-9372-4834-aeae-f00e2351ea79)

### RESULT
Thus the python program was successfully created.
