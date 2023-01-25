# command-line-arguments-to-count-word

## AIM:

To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:

Import sys

### Step 2: 

Initially make count = 0
 
### Step 3: 

Open the content file using command line arguments.

### Step 4:  

By using for loop name the function as "line"

### Step 5: 

Split the line using .split

### Step 6: 

Count the length of the word and print it

## PROGRAM:
```
#Developed by:  P SRI VARSHAN
#ROLL NO:22008051

import sys
count=0
with open(sys.argv[1],'r') as f:
        for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)
```

### OUTPUT:

#### Text File

![image](https://user-images.githubusercontent.com/114944059/214647925-759d9f05-681b-40f3-8ffd-660b5e8a843d.png)

#### Code File

![sri 5b](https://user-images.githubusercontent.com/114944059/214648125-c64bc9f5-5392-4397-90e6-816e6787feef.png)


## RESULT:

Thus the program is written to find the word count from the contents of a file using command line arguments.
