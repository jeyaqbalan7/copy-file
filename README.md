# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Open the file f1 in read mode.

### Step 2: Open the file f2 in append mode.
 
### Step 3: Copy the contents using write() with the for loop. 

### Step 4: End the program.  

## PROGRAM:
```
#Developed By: Jeyabalan
#Register No: 212222240040
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
### FILE1:
![image](https://github.com/jeyaqbalan7/copy-file/assets/119393851/06bd918b-8e07-43b2-8645-2523f6fa24da)

### FILE2:
![image](https://github.com/jeyaqbalan7/copy-file/assets/119393851/54ca9b83-7429-42ba-8072-1c533aed025c)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
