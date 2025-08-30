# Experiment-4
## ARMSTRONG NUMBER 
# Aim: Write a python program to check the number is Armstrong number or not and inspect for failures. 

# Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

# Program
```
num = int(input("Enter a number: "))
num_str = str(num)
power = len(num_str)
armstrong_sum = sum(int(digit) ** power for digit in num_str)
if num == armstrong_sum:
    print(num, "is an Armstrong number.")
else:
    print(num, "is not an Armstrong number.")

```
# Output

<img width="323" height="72" alt="Screenshot (426)" src="https://github.com/user-attachments/assets/c02d27b8-4c63-4293-9f7d-a5b8f7cc62ce" />


<img width="306" height="52" alt="Screenshot (427)" src="https://github.com/user-attachments/assets/2218d892-886f-4c5a-ba85-0668406b4651" />


# Result
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.
