# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function:
## PROGRAM:
Program for copying the contents from one file to another file
Developed by: SUBASH R
RegisterNumber: 23003821

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
### OUTPUT:
![292654615-21bb55fa-1dd3-499d-9576-cd6a5aa43464](https://github.com/AkilaMohan/copy-file/assets/147139828/97dee65e-c3e4-440a-839f-0613278296a0)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
