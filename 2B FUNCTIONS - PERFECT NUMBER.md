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
def perfect_num(num):

sume=0   <br>
for i in range(1,num):   <br>
    if (num%i==0):   <br>
        sume=sume+i  <br>
if(sume==num):  <br>
    print("The number is a Perfect number!")   <br>
else:  <br>
    print("The number is not a Perfect number!")  <br>
num=int(input())
perfect_num(num)

```
### OUTPUT
![image](https://github.com/user-attachments/assets/6d7dc47b-4273-4de1-9a50-9413a47d0a75)


### RESULT
Thus the Python program to check whether a number is a Perfect Number using functions was executed successfully and the output was verified.
