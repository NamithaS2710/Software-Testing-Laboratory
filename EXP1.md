# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212221040110

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
```
i.)do…while: 
def display(): 
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ") 
if start.isnumeric() and end.isnumeric(): 
while True: 
start=int(start) 
end=int(end) 
print(start,end=‘ ‘) 
if start<end: 
start+=1 
else: 
break 
else: 
print("Enter a valid positive number.") display()

ii.) while…do 
start=input("Enter a positive value for START: ") end=input("Enter 
a positive value for END: ") 
if 
start.isnumeric() 
start=int(start) 
end=int(end) 
while start<end: 
print(start) 
start+=1 
else: 
and end.isnumeric(): 
print("Enter a valid positive number.")

iii.) switch 
def switch(): 
switcher={ 
0:"even", 
1:"odd" 
} 
n=input('Enter a value for N: ') try: 
n=int(n) 
print(switcher[n%2]) 
except ValueError: 
print("Enter a valid number.") 
switch()

iv.) if else 
def compare(): 
a=input("Enter a value for A: ") 
b=input("Enter a value for B: ") 
try: 
a=int(a) 
b=int(b) 
if a>b: 
print("A is greater than") 
elif a<b: 
print("B is greater than") 
else: 
print("A is equal to B") 
except ValueError: 
print(“Enter a valid number.”)

v.) for 
def iterate(): 
string=input("Enter a string: ") for 
i in string: 
print(ord(i),end=" ") 
iterate() 
```

### Output:
![image](https://github.com/user-attachments/assets/16e8921c-d0d9-448b-bebe-c8e98b4cdf19)
![image](https://github.com/user-attachments/assets/c1fd4e2c-0850-4a5a-997a-a7bb905e9f35)
![image](https://github.com/user-attachments/assets/815ca5c5-bc78-424c-928d-20ab357bd1a9)
![image](https://github.com/user-attachments/assets/c48e11ea-b388-4240-8158-bc69c61b1aeb)
![image](https://github.com/user-attachments/assets/514f3a07-9758-4481-9f4a-09ce675547ce)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


