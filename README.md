# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open the text file that you want to copy
### Step 2: 
by using read function read the file 
### Step 3: 
now open the file that you want to store the copied text
### Step 4:  
by using write function write the file
### Step 5: 
now open the second file to see the copied text
## PROGRAM:
```
# program to copy text from one file to another
# NAME : Keerthika M P
# Reg no : 212223240071
with open("file1.txt","r") as f1:
    msg1=f1.read()
with open("copy.txt","w") as f2:
    f2.write(msg1)
```
### OUTPUT:
![image](https://github.com/Keerthika23013559/Copy-File/assets/162658262/e458f5b2-c2f7-40e5-972a-5e38d60fe4cc)

![image](https://github.com/Keerthika23013559/Copy-File/assets/162658262/fe536238-4b1d-4231-9223-666dd495da2d)

![image](https://github.com/Keerthika23013559/Copy-File/assets/162658262/38d6f651-8d22-469c-b8ab-f8eaa739ab67)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
