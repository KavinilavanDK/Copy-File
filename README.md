## DATE:
# EX:11 - Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7 
## ALGORITHM: 
### Step 1:
Create a text file with some content in it.
### Step 2: 
Open the created text file.
### Step 3: 
Create another empty text file.
### Step 4:  
Copy the content of text file to empty file using write function.
### Step 5: 
Check th output of the program.
### Step 6: 
Then close the file
## PROGRAM:
```
#Python program for copying the contents from one file to another file.
#Developed by: MONISH N
#Register Number: 212223240097
with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![Screenshot 2024-10-16 152855](https://github.com/user-attachments/assets/94ef7490-65b9-4f9a-b9b9-cad29489a144)
![Screenshot 2024-10-16 152957](https://github.com/user-attachments/assets/0dfdc848-3e97-4205-a072-57850c970e27)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
