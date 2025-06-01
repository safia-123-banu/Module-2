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

```
a=int(input())
b=int(input())
f=lambda a,b: (f"{a} is smaller than {b}")
if a<b else(f"{a} is greater than {b}" if(a>b)
else(f"{a} is equal to{b}"))
print(f(a,b))
```

### OUTPUT

![image](https://github.com/user-attachments/assets/80d3ae9e-5a84-4848-8d1e-22e685bd5e7a)


### RESULT

Thus the Python program using a lambda function to compare two numbers and display their relation was executed successfully and the output was verified.
