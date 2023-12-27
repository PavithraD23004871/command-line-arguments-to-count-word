# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import the sys module
### Step 2: 
Pass the filename as the first argument after the name of script.open the file as sys.argv[1] 
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words
### Step 5: 
Use len() to find the total words
### Step 6: 
Run the program to determine the number of words in the file created
## PROGRAM:
Developed by : pavithra.D
Registered number : 212223230146

import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
### OUTPUT:
![WhatsApp Image 2023-12-27 at 18 29 09_ddf445f5](https://github.com/PavithraD23004871/command-line-arguments-to-count-word/assets/138955967/879c3a68-522c-4706-be2e-aca974574c22)
![WhatsApp Image 2023-12-27 at 18 30 21_3c9f7b8d](https://github.com/PavithraD23004871/command-line-arguments-to-count-word/assets/138955967/b53a7f7a-8b11-4585-89c4-ec2cd4b508d9)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
