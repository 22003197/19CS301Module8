# Exp.no: 37
## HACKERRANK CHALLENGES-2.

### AIM

To write python program to print the numbers in reverse order(without in-built funtion).

### ALORITHM 

1. Start the program.

2. Read an integer n.
  
3. While n > 0:
   a. Print the last digit: n % 10 (without newline).
   b. Remove the last digit: n = n // 10.

4. End loop when all digits are processed.

5. Terminate the program.
   
### PROGRAM

```
n = int(input())
while(n>0):
    print(n%10,end="")
    n=n//10
```

### OUTPUT

![image](https://github.com/user-attachments/assets/a742a89e-d3de-443b-86b1-bcbaa5650973)

### RESULT

Thus the python program was successfully created.
