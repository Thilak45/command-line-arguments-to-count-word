# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words.

### Step 6:
Run the program to determine the number of words in the file created.

## PROGRAM:
```
'''
Developed by : tilak vellachi
Registered number : 23009564
'''
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:

![Screenshot 2023-12-24 181848](https://github.com/Thilak45/command-line-arguments-to-count-word/assets/138849161/f6f7152b-70f9-4ce7-bea9-db288ea7cd53)
![Screenshot 2023-12-24 180320](https://github.com/Thilak45/command-line-arguments-to-count-word/assets/138849161/d8e14668-10cb-4b11-ba3b-d939bb22cfc1)
![Screenshot 2023-12-24 180742](https://github.com/Thilak45/command-line-arguments-to-count-word/assets/138849161/4e6faaef-ed88-452b-8f15-6928d4b6295d)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
