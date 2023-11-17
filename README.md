# EXP-5c copy-file
## Date: 18.10.2023
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: First we need to open the required file form which we need to copy the text. Again using the with keyword to open the empty file.

### Step 2: Using keyword "with" to open the requied file.
 
### Step 3: Again using the with keyword to open the empty fil

### Step 4: The empty file is open by using 'W' which is used to write only.

### Step 5: The four function is used to take each line from the main fi

### Step 6: The four function is used to take each line from the main file.

## PROGRAM:
```
#Developed by: Richardson A
#Reference no: 212222233005
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```

### OUTPUT:

![image](https://github.com/Richard01072002/copy-file/assets/141472248/fd3817ae-39f6-42ca-b06e-cb257e3d06b1)

![image](https://github.com/Richard01072002/copy-file/assets/141472248/f59f48d7-b1d0-487e-918e-2a35c1df35c9)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
