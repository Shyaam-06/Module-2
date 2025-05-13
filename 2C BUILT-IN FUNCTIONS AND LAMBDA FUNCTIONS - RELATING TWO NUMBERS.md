# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS


### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.


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

a = eval(input("Enter the first number: "))

b = eval(input("Enter the second number: "))

compare = lambda x, y: "greater than" if x > y else ("less than" if x < y else "equal to")


result = compare(a, b)


print(f"The first number is {result} the second number.")

### OUTPUT

![image](https://github.com/user-attachments/assets/bcd89cf3-939d-471d-9ce8-81ba4eddecd3)


### RESULT

Thus the Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function was written and excecuted successfully.
