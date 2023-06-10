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
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![image](https://github.com/DHARINIPV/command-line-arguments-to-count-word/assets/119400845/455c325c-5ffd-4253-93cf-0f15cfde975b)

![image](https://github.com/DHARINIPV/command-line-arguments-to-count-word/assets/119400845/033909c7-83c7-4cd9-a47a-c2bd7a25e85a)

![image](https://github.com/DHARINIPV/command-line-arguments-to-count-word/assets/119400845/a39193cb-97a3-4d99-a6c6-24e5dfe08966)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
