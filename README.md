# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.

### Step 2:
Open the existing file to read.

### Step 3:
Open the new file to write.

### Step 4:
Copy the contents from existing file to new file.

### Step 5:
Get the inputs from the user for existing file and new file. Call the function.

### Step 6:
End the program.

## PROGRAM:
```
Write a python program for copying the contents from one file to another file.
Develop bY: K.HEMANATH
Register no: 212223100012
with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![output 1](https://github.com/Hemanath08/Copy-File/assets/151807176/77952961-da6a-4743-bd4a-6c0eebcc8c82)
![output 2](https://github.com/Hemanath08/Copy-File/assets/151807176/b6c5c4b0-7d9a-4378-ba32-24dfd5c54ae5)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
