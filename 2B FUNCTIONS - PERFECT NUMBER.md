# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No: 212222060292
#Name: Vijay Aravind S
#Add your Code Here
def result(a, b):
    d = a % b
    print(f"Modulo is {d}")

a = int(input())
b = int(input())
result(a, b)


```
### OUTPUT
<img width="574" height="242" alt="image" src="https://github.com/user-attachments/assets/aa929424-9dd0-4eb4-a64a-b1bc538ebf06" />


### RESULT
Thus the program to define a function that accepts two values and returns their modulo value has been implemented and executed successfully.

