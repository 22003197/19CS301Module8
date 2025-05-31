# Exp.no: 39
## HACKERRANK CHALLENGES-4

### AIM

To develop a python program to count the number of vowels and consonants from the given string.

### ALORITHM 

1. Start the program.
   
2. Read a string s.

4. If i is a vowel increment vowel.
   
5. Else, increment consonant.

6. Print the number of vowels v and number of consonants c.

7. Terminate the program.
   
### PROGRAM

```
def fun(s):
    v,c=0,0
    for i in s:
        if i in ['A','E','I','O','U','a','e','i','o','u']:
            v+=1
        else:
            c+=1
    print("Number of Vowels:",v)
    print("Number of Consonants:",c)
s=input()
```

### OUTPUT

![image](https://github.com/user-attachments/assets/57420517-def0-45ce-884c-2bf0b68056f5)

### RESULT
Thus the python program was successfully created.
