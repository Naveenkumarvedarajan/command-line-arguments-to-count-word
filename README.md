# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific location of interest
Step 2:
On the same location as the text file, create a python program file
Step 3:
In python Program,import sys and open a text file with argument "sys.argv[1]"
Step 4:
Using read() and split (),split the lines in the file into a sequence of words
Step 5:
Using len() count the number of words in the text file
Step 6:
In command prompt,initiate python followed by program name and tet file name to get the output

### Step 2: 
On the same location as the text file, create a python program file
 
### Step 3: 
In python Program,import sys and open a text file with argument "sys.argv[1]"

### Step 4:  
Using read() and split (),split the lines in the file into a sequence of words

### Step 5: 
Using len() count the number of words in the text file

### Step 6: 
In command prompt,initiate python followed by program name and tet file name to get the output

## PROGRAM:
Python program for getting the word count from the contents of a file using command li
Developed By: Naveen kumar V
Register Number: 23000827
import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))

### OUTPUT:

![image](https://github.com/Naveenkumarvedarajan/command-line-arguments-to-count-word/assets/147140428/87e42a64-5cde-41fa-ad23-906a12214501)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
