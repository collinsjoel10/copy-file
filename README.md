# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Create two txt file.A file which has content [lines.txt] to be copied to the empty [text.txt]file.

Step 2: Using write() function to copy the content from line.txt to empty file,text.txt.

Step 3: Save and run the python program in terminal.

Step 4: The text from the lines.txt file is copied to the empty file text.txt.

Step 5: Then the text is shown in empty file text.txt.

PROGRAM:
```
'''Program For Copying The Contents:
Developed by: joel p
RegisterNumber: 22008934'''

print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()

fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")
```

### OUTPUT:
![ae22981b-dd02-40e4-8871-59e47792305b](https://user-images.githubusercontent.com/118626456/214859929-a7677e7d-44c8-4cd6-9983-ef5ea90e2cb5.jpg)

![ca78e361-e80d-4911-aa2b-a7d17166caa8](https://user-images.githubusercontent.com/118626456/214859942-94a0bab3-b27d-4392-8b68-4323611e54ee.jpg)

![149033ab-5d79-412e-8d83-d23fb77b4aee](https://user-images.githubusercontent.com/118626456/214859952-b9a492c7-988f-4820-b119-40dad311c7ce.jpg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
