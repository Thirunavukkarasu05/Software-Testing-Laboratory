# Ex.No: 7  SORTING
### DATE:    08/05/2025                                                                        
### REGISTER NUMBER : 212222040173
### AIM: 
Write a python program for sorting and inspect for failures.

### Algorithm: 

1. Start the program. 
2. Get the number of elements from user 
3. Get the elements to be sorted 
4. Traverse the array and sort the elements one by one 
5. Print the sorted array 
6. Stop the program.

## Program:
```
try:
    n = int(input("Enter the number of elements: "))
    arr = []

    for i in range(n):
        a = float(input("Enter the element: "))
        arr.append(a)

    # Bubble sort
    for i in range(n):
        for j in range(n - 1):  # Use n - 1 to avoid index out of range
            if arr[j] > arr[j + 1]:  # Corrected the logic
                temp = arr[j]
                arr[j] = arr[j + 1]
                arr[j + 1] = temp

    print("The array after sorting: ")
    for i in range(n):
        print(arr[i], end=' ')

except ValueError:
    print("Enter a valid number")

```
### Output:
![Screenshot 2025-05-15 082455](https://github.com/user-attachments/assets/96363d91-0fca-4d5c-877e-439a8c7170a4)



### Result:
Thus, the python program for sorting and inspect for failures.verified successfully

