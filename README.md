# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.
### Step 2:
Give a new file name to create a copy of a file content.
### Step 3: 
Read the file and close the file.
### Step 4: 
Now write the content in the new file.
### Step 5: 
When done print"File copied successfully".
### Step 6: 
End of the program

## PROGRAM:
```py
#To write a program for copying the contents from one file to another file.
#Developed by: Ananda Rakshan K V
#RegisterNumber: 212223230014
with open("file3.txt","r") as fp: 
    x = fp.read()
with open("file31.txt","w") as fp1: 
    fp1.write(x)
```
### OUTPUT:
![](./python_5c_3.png)
![](./python_5c-1.png)
![](./python_5c_2.png)
## RESULT:
Thus the program is written to copy the contents from one file to another file.