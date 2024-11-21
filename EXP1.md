# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE : 16-08-2024                                                                           
### REGISTER NUMBER : 212221040070

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
def display():
start=input("Enter a positive value for START: ")
if start.isnumeric():
end=input("Enter a positive value for END: ")
if end.isnumeric():
while True:
start=int(start)
end=int(end)
print(start,end=' ')
if start<end:
start+=1
else:
break
else:
print("The value",end,"is not a positive number.")
else:
print("The value",start,"is not a positive number.")
display()
```


### Output:
```
Python 3.10.4 (tags/v3.10.4:9d38120, Mar 23 2022, 23:13:41) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.

 RESTART: C:\Users\M PAVITHRA\OneDrive\stl\stl ex1.py
 
Enter a positive value for START: 5
Enter a positive value for END: 5
5 

Enter a positive value for START: hi
Enter a positive value for END: hello
Enter a valid positive number.

Enter a positive value for START: 0
Enter a positive value for END: 5
0 1 2 3 4 5 

Enter a positive value for START: 5.5
Enter a positive value for END: 4.5
Enter a valid positive number.

Enter a positive value for START: -4
Enter a positive value for END: -6
Enter a valid positive number.

Enter a positive value for START: 3
Enter a positive value for END: 10
3 4 5 6 7 8 9 10 

Enter a positive value for START: 
Enter a positive value for END: 
Enter a valid positive number.
 
Enter a positive value for START: 4
Enter a positive value for END: #
Enter a valid positive number.

Enter a positive value for START: l
Enter a positive value for END: 3
Enter a valid positive number.

Enter a positive value for START: 4
Enter a positive value for END: 0
4 
```

![Screenshot (50)](https://github.com/user-attachments/assets/50d9c787-e5ca-47e2-afdb-1a1860e2e622))

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


