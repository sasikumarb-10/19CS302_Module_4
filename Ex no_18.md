# EX 18 C program to find frequency of a character in the given input.
## DATE:
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1. Start. 
2. Define the required variable. 
3. Write program to find frequency of a character. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.

## Program:
```
/*
C program to find frequency of a character in the given input.
Developed by: Sasi Kumat B
RegisterNumber:  212223060252
*/

#include<stdio.h> 
#include<string.h> 
int main() 
{ 
int i,count=0,len; 
char str[100],val[100];  
scanf("%s %s",str,val);  
len=strlen(str);  
for(i=0;i<len;i++){ 
if(str[i]==val[0])  
count++; 
}printf("%d",count);} 
```

## Output:

![image](https://github.com/user-attachments/assets/03b1784a-0c6a-4b21-bc9b-cb2d3e311bbf)


## Result:
Thus the program was executed and the output was verified successfully.
