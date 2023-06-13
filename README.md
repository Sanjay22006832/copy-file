# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

Step 1:

Create a 1.txt with some content in it

Step 2:

Open the 1.txt file in read mode

Step 3:

Create a copy.txt file using write mode

Step 4:

Copy the content of 1.txt file to copy.txt using write function

## PROGRAM:

Program for copying the contents from one file to another file
Developed by: Sanjay.M
RegisterNumber: 212222240090

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)

### OUTPUT:

![image](https://github.com/Sanjay22006832/copy-file/assets/119830477/bbdae8b1-447c-4290-9652-b28e705dc2c9)

![image](https://github.com/Sanjay22006832/copy-file/assets/119830477/98bf8b79-774b-476d-abe9-4cc87d183e0f)

![image](https://github.com/Sanjay22006832/copy-file/assets/119830477/7d2ec5a6-c37a-4e38-afb8-0c4cb3fff14e)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
