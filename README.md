# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
 Read the file and store in a variable.

### Step 3: 
Now create a new file in which we want to paste the content using write access mode.

### Step 4:  
Use write function to copy the read file that has been stored in the variable.

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6: 
End the program.

## PROGRAM:
```python
#python program for copying a file
#developed by:NAVEEN S
#registration number:212222240070
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)  
```
###FILE:
![ex5(c)(a)(p)](https://github.com/Naveensrinivasan07/copy-file/assets/119475891/3507a84a-5892-44d7-bf61-5c41bd585b1b)

### OUTPUT:
![OUT](https://github.com/Naveensrinivasan07/copy-file/assets/119475891/6ad570fa-192f-45a3-986b-3297096eb19b)

