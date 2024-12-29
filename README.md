# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
```
#Developed by:R N SOMNATH
#Register Number: 24000580

def copy(fname,newfile):
    with open(fname) as fp:
        with open (newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("file1.txt","file2.txt")
```

### OUTPUT:
![image](https://github.com/user-attachments/assets/d098a391-9699-46bd-99a6-1a243af9e672)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
