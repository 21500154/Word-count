# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Open a text file in read mode only.
Using file = open("wordcount.txt","r") we can open the file in a read-only mode and store this information in a file variable.
### Step 2: 

Using file = open("wordcount.txt","r") we can open the file in a read-only mode and store this information in a file variable.

### Step 3: 
read_data = file.read() this statement is used to read the entire data in one go and store it in a variable named read_data.

### Step 4:  

per_word = read_data.split() this statement is used to split the sentences into words using split().
per_word is the variable where the informations are stored.
### Step 5: 

To print the count of total words we use len().
len(per_words) gives the length of per_word variable .

### Step 6: 

Note that length is counting total words in the file.
## PROGRAM:
```
file=open("wordcount.txt","r")
read_data=file.read()
per_word=read_data.split()
print("Total Words:",len(per_word))
```
### OUTPUT:

![wcop1](https://user-images.githubusercontent.com/93427345/153755597-b0d7acc2-e0d7-4e96-bd0d-fc594bc8b245.png)


### Text file:

![wordcop](https://user-images.githubusercontent.com/93427345/153755611-95e80ec8-f09e-4e23-b3d7-b1b2a43b1a3d.png)



## RESULT:
Thus the program is written to find the word count from a text.
