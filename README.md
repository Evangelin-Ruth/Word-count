# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file add sentence to it
### Step 2: 
 Using open() open the .txt file in read mode in Python compiler
### Step 3: 
Assign a variable for value zero
### Step 4:  
Using the for loop assigning the fp then use variable to split the content
### Step 5: 
Iterate in nested loop to increment the variable
### Step 6: 
Print the variable

## PROGRAM:
To write a program for getting the word count from a file.
Developed by: Evangelin.S
RegisterNumber: 212221230025

def wordcount():
    cnt = 0
    with open("MyFile.txt","r") as fp:
        data = fp.read()
        for line in data.split():
            cnt += 1
    print("The number of words in the given file is:",cnt)
wordcount()
### OUTPUT:
![image](https://user-images.githubusercontent.com/94219798/154706221-c65ab050-a805-44ac-981e-d74e005c4b40.png)



## RESULT:
Thus the program is written to find the word count from a text.
