# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
##Step 1:
Create a txt file to count the number of word in that file.

##Step 2:
Open the txt file in read mode using open().

##Step 3:
Using split() function to split the words in the txt file and count it.

##Step 4:
Save the python program using .py extention.

##Step 5:
Run the python program in terminal to get the output.

##Step 6:
Number of words in the txt file is displayed as the output.

## PROGRAM:

## Developed by: Manoj karthik R
## Reg no:22003728
```
num_words =0
with open('python.py','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={0}".format(num_words))

```
### OUTPUT:
![image](https://user-images.githubusercontent.com/119560395/214845158-13c95688-3388-4191-906c-55537d276e9a.png)


## RESULT:
Thus the program is written to find the word count from a text.
