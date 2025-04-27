# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM
```
n=int(input())
result=tuple(i for i in range(5,n,5))
print(result)
```
### OUTPUT
![Screenshot 2025-04-27 155141](https://github.com/user-attachments/assets/c7f8caf0-cc76-4b4e-909b-64b2b09d159f)
### RESULT
Thus  Python program to create a tuple containing all multiples of 5 up to a given number N has been implemented and executed successfully.
