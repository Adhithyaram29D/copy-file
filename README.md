# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
Open the file f2 in append mode.
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program.
## PROGRAM:
```python
#Developed By: AdhithyaRam D
#Register No: 212222230008
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```           
### OUTPUT:
### FILE1:
![Screenshot 2023-06-08 233117](https://github.com/Adhithyaram29D/copy-file/assets/119393540/384d0adf-6391-4970-93e7-46376552c4b1)
### FILE2:
![Screenshot 2023-06-08 233126](https://github.com/Adhithyaram29D/copy-file/assets/119393540/8dc3e7cb-7507-417e-a062-da0a270ef2e2)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
