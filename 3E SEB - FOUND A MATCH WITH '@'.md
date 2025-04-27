# Exp.No:3e
## SEB - UPPER CASE LETTERS JOINED WITH '@'

---

### AIM  
To write a Python function to find sequences of Upper case letters joined with a '@'.

---

### ALGORITHM
1. Start.
2. Input a string a from the user.
3. Convert the string a to uppercase (to handle any lowercase input).
4. Initialize a flag variable b = 0.
5. For each character i in string a, do:
         If the character i is '@' and '@' is also in the original string:
         Set b = 1 (indicating a match is found).
6. If b == 1, then:
     Print "Found a match".
7. Else:
     Print "Not matched".
8. End
### PROGRAM

```
a=input()
b=0
c=a.upper()
for i in a:
    if (i=='@') and c==a:
        b=1
if b==1:
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT
![Screenshot 2025-04-27 160632](https://github.com/user-attachments/assets/d53c18ee-f5e6-4b61-8e50-5670705af779)
### RESULT
Thus the python program to find sequences of Upper case letters joined with a '@' has been implemented and executed successfully.
