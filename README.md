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
Use len() to find the total words.

## PROGRAM:
```
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: vasanth s
RegisterNumber:212222110052

import sys
fp=open(sys.argv[1])
data=fp.read()
words=data.split()
print("no of words",len(words))
```

### OUTPUT:
<img width="358" alt="1" src="https://github.com/vasanth0908/command-line-arguments-to-count-word/assets/122000018/953cdc73-dd79-4fca-a6dc-a6e5b7a378d4">




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
