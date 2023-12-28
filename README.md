# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file using notepad with extension.py
### Step 2: 
open google colab and mount the drive for using the create file 
### Step 3: 
now open the text file and store the data in variable
### Step 4:  
Then read the content in the file and store the data in variable
### Step 5: 
now open the newcreated file or an empty file using a different file object by "W+" mode and write the content derived from file using write()
### Step 6: 
end og the program
## PROGRAM:
```
f=open("/content/drive/Mydrive/record/record file.txt","r")
content=f.read()
f1=open("/content/drive/Mydrive/record/record file updated.txt","w+")
f1.write(content)
print("the content that has been copied to the new file is:",content)
```
### OUTPUT:
![image](https://github.com/23008859/copy-file/assets/139117979/c2a58f38-cb3c-4b7c-8d6f-b4078381ac57)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
