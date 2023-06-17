# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module.
### Step 2: 
 Open the file with sys.argv[1].
### Step 3: 
Use the for loop to select the content in file.
### Step 4:  
Use split function to to separate the file content into words or strings.
### Step 5: 
Count the length of the words using len.
### Step 6: 
Print the number of words.
## PROGRAM:
Program for getting the word count from the contents of a file using command line arguments.

Programmed by: Dharini PV

Ref.No.: 212222240024
```
import sys
fp=open(sys.argv[1],"r")
d={}
for i in fp:
  for w in i.split():
    if w not in d.keys():
      d[w]-1
  else:
       d[w]+=1
  print(d)
```
### OUTPUT:

![image](https://github.com/DHARINIPV/command-line-arguments-to-count-word/assets/119400845/c3d64c01-38b6-4e49-8a3a-133f940fd66c)

![image](https://github.com/DHARINIPV/command-line-arguments-to-count-word/assets/119400845/f52b5c23-84c4-4d69-bc01-52c63c52ec3b)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
