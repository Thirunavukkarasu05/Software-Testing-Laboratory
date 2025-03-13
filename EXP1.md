# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 13.03.2025                                                                        
### REGISTER NUMBER : 212222040173

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
### do…while
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        if start <= end:  # Ensuring valid range
            while start <= end:
                print(start, end=' ')
                start += 1
        else:
            print("START should be less than or equal to END.")
    else:
        print("Enter a valid positive number.")
display()
```
### while do
```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric(): 
    start = int(start)
    end = int(end)

    if start <= end:  # Ensuring a valid range
        while start <= end:
            print(start)
            start += 1
    else:
        print("START should be less than or equal to END.")
else:
    print("Enter a valid positive number.")
```
### for
```
def iterate(): 
    string = input("Enter a string: ")  
    for i in string: 
        print(ord(i), end=" ")  # Print ASCII values of characters
iterate()
```
### if else
```
def compare(): 
    a = input("Enter a value for A: ") 
    b = input("Enter a value for B: ") 
    
    try: 
        a = int(a) 
        b = int(b) 
        
        if a > b: 
            print("A is greater than B") 
        elif a < b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    
    except ValueError: 
        print("Enter a valid number.")
compare()
```
### switch
```
def check_even_odd():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(f"The number {n} is {switcher[n % 2]}.")
    except ValueError:
        print("Enter a valid number.")
check_even_odd()
```









### Output:
![1a](https://github.com/user-attachments/assets/47ba7a06-6bed-47a4-a88b-c5b7cf66683c)
![1b](https://github.com/user-attachments/assets/600ba3d6-7f04-4400-bb22-2f9cdfb7f662)
![1d](https://github.com/user-attachments/assets/697f36de-2451-40e0-994e-d6397a0b296e)
![1c](https://github.com/user-attachments/assets/e0ee6f87-0385-4fa1-a9dc-66753ef864e9)
![1e](https://github.com/user-attachments/assets/692938bd-379f-4df9-aff0-60f67069e7f8)






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


