# command-line-arguments-to-count-word

## AIM:

To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 

Step 1: Import sys module.

Step 2: Open the file with sys.argv[1].

Step 3: Use the for loop to select the content in file.

Step 4: Use split function to to separate the file content into words or strings.

Step 5: Count the length of the words using len.

Step 6: Print the number of words.

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments.
Programmed by: PREM KUMAR k
Ref.No.: 212222230111

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![image](https://github.com/premkumarkarthikeyan/command-line-arguments-to-count-word/assets/119476243/ad1099fe-62f2-486f-8a63-ae3f23b99a31)
![image](https://github.com/premkumarkarthikeyan/command-line-arguments-to-count-word/assets/119476243/72e29ecf-b121-48f0-94bf-01142dfe21e5)
![image](https://github.com/premkumarkarthikeyan/command-line-arguments-to-count-word/assets/119476243/73fdef17-15eb-40dc-ab25-d3a05abd44af)
## RESULT:

Thus the program is written to find the word count from the contents of a file using command line arguments.
