# 19CS301Module8
EXPTNO.8a Program to find Find the simple interest

### Aim: To Write a Python Program to find Find the simple interest by getting the principal, rate and time value from the user
### Algorithm:

STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create variable 'p','r','t' for principal,rate of interest and time. STEP 4: Get the input of p,r and t from user.

STEP 5 : Using the formula (p*r*t)/100 calculate the result. STEP 6: Print the result.

STEP 7: Stop.

### Program:
```
reg no:212223070023
name:Saran Krishna P S
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the rate of interest: "))
time = float(input("Enter the time period (in years): "))

simple_interest = (principal * rate * time) / 100

print(f"The simple interest is: {simple_interest}")


```
### Output:
![image](https://github.com/user-attachments/assets/e037a993-bfc9-4895-bd21-1528197ab431)


### Result: Thus, the given program is implemented and executed successfully .

EXPTNo.8b program to display elements from a list, present at odd index positions

### Aim: To Write a python program to display elements from a list, present at odd index positions
### Algorithm:

STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a list and a variable a.

STEP 4: Get the input of a from user.

STEP 5 : Using loop get the inputs and append in list.

STEP 6: Using another loop print the elements in the odd index position of the list. 

STEP 7: Stop.

### Program:
```
reg no:212223070023
name:Saran Krishna P S 
lst = [10, 20, 30, 40, 50, 60, 70]
print([lst[i] for i in range(1, len(lst), 2)])

```
### Output:
![image](https://github.com/user-attachments/assets/4f448634-841c-4ed3-8e7a-4f48658d15e2)

### Result: Thus, the given program is implemented and executed successfully .
 

EXPT NO>8C To Write a python program to Given the participants'	score sheet for your University Sports Day, you are required to find the runner-up score
### Aim: To Write a python program to Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given scores. Store them 
         in a list and find the score of the runner-up.


### Algorithm:
STEP 1: Start.

STEP 2: Create a variable n.

STEP 3: Get the value of n from user.

STEP 4: Get the number of inputs from user and split the input and append in a list. STEP 5: Using set function remove duplicates from the list.

STEP 6: Using sort function reorder the list in ascending order. STEP 7: Print the result.

STEP 8: Stop.


### Program:
```
reg no:212223070023
name:Saran Krishna P S
scores = list(map(int, input().split()))
scores.sort()
runner_up = scores[-2]
print(runner_up)


### Output:
 ![image](https://github.com/user-attachments/assets/4ae98a86-c951-4b7b-b6b7-22dde3330c09)


### Result: Thus, the given program is implemented and executed successfully .
 


EX: 8.d program to square all the even numbers and cube all odd numbers from a list of integers
### Aim: To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.


### Algorithm:

STEP 1: Start.

STEP 2: Create a variable f and l for upper and lower limit of list. STEP 3: Get the value of f and l from user.

STEP 4: Create a list.

STEP 5 : Get the input from user and append in the list. STEP 6: Create a lambda function to calculate the result. STEP 7: Print the result.

STEP 8 : Stop.

### Program:
```
reg no:212223070023
name:Saran Krishna P S 
start = int(input("Enter the starting range: "))
end = int(input("Enter the ending range: "))

lst = [i for i in range(start, end+1)]

result = [x**2 if x % 2 == 0 else x**3 for x in lst]

print(result)



```
### Output:
![image](https://github.com/user-attachments/assets/ddbd36e3-8f55-4166-8f95-1d1f53d2a86a)

### Result: Thus, the given program is implemented and executed successfully .


EX: 8.e check whether they are valid mobile numbers.

### Aim: Write a Python program to check whether the given mobile numbers are valid or not.
A valid mobile number is a 10-digit number starting with 7, 8, or 9.

---

### Algorithm:

1. **Start**
2. Read the number of test cases $t$.
3. For each test case, do the following:

   * Read the mobile number as a string.
   * Define a regular expression pattern to match:

     * Start of the string `^`
     * First digit is either 7, 8, or 9: `[789]`
     * Followed by exactly 9 digits: `\d{9}`
     * End of the string `$`
   * Use the regex to check if the mobile number matches the pattern.
   * If it matches, print "YES".
   * Otherwise, print "NO".
4. **End**

---

### Program:
reg no:212223070023
name:Saran Krishna P S
import re
num=int(input())
for i in range(num):
    n=input()
    p=re.compile("[7|8|9]\d{9}")
    if re.match(p,n):
        print("YES")
    else:
        print("NO")

### Output:
![image](https://github.com/user-attachments/assets/8429d2c4-7739-488d-9013-80a05754ebb4)


### Result: Thus, the given program is implemented and executed successfully .
 




