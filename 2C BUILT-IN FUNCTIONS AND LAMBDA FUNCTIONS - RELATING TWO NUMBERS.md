# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM
Reg.No: 212222060292
#Name: Vijay Aravind S
#Add your Code Here
compare = lambda a, b: (
    f"{a} is greater than {b}" if a > b 
    else (f"{a} is smaller than {b}" if a < b 
    else f"{a} is equal to {b}")
)

input1 = int(input())
input2 = int(input())
print(compare(input1, input2))


### OUTPUT
<img width="624" height="229" alt="image" src="https://github.com/user-attachments/assets/82d194dd-0dbc-4df2-be20-b8f07b63f8be" />


### RESULT
Thus the program to check the relation between two number using lambda function has been implemented and executed successfully.
