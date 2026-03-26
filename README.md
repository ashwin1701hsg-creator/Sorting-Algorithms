# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
arr=[64,25,1,100,11]
for i in range(len(arr)):
    mini=i
    for j in range(i+1,len(arr)):
        if(arr[j] < arr[mini]):
            min=j
            
    arr[i], arr[mini] = arr[mini], arr[i]

print("Sorted array:\n  ", arr)




```
## Output:
<img width="453" height="152" alt="image" src="https://github.com/user-attachments/assets/9777931e-f55a-4432-bf78-cd47c49ef5ff" />

ii)	#Insertion Sort
```
arr = [64, 25, 12, 22, 11]
for i in range(1, len(arr)):
    key = arr[i]
    j = i - 1
    while j >= 0 and arr[j] > key:
        arr[j + 1] = arr[j]
        j -= 1
    arr[j + 1] = key
print("Sorted array: \n ", arr)





```

## Output:
<img width="455" height="180" alt="image" src="https://github.com/user-attachments/assets/dea9b0ae-b208-47cc-9ce8-1f493ffc305e" />


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
