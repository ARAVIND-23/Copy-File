# Copy-File
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
## PROGRAM:
with open("aliya.txt",'r') as file1:
    msg=file1.read()
with open("aliyanew.txt",'w') as file2:
    file2.write(msg)
### OUTPUT:


![Screenshot 2024-05-19 162805](https://github.com/ARAVIND-23/Copy-File/assets/138970182/b85aa86d-1f83-4300-aa19-eccb2891ec6c)

![Screenshot 2024-05-19 162818](https://github.com/ARAVIND-23/Copy-File/assets/138970182/864a016a-97b4-4762-8f1f-53f2b52a5cf9)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
