# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
1.Start the program and declare a file pointer.

2.Use fopen() in write mode to create and open the file "Hospital.txt".

3.Check if the file was created and opened successfully and display a message.

4.Close the file using fclose() after confirming successful opening.

5.Display a message indicating the file was closed successfully.

## Program:
```
/*
C program to calculate the area of a triangle using pointer.
Developed by: ARAVINDHAN
RegisterNumber:  212222063001
*/
#include <stdio.h> 
int main() { 
float a, b, c, min; 
scanf("%f%f%f", &a, &b, &c); 
// Finding minimum using conditional operator 
min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c); 
 
printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min); 
return 0; 
} 
```

## Output:

<img width="661" height="181" alt="image" src="https://github.com/user-attachments/assets/3f04e129-9aee-41e4-935c-ad8b6894e6d2" />


## Result:
Thus the program was executed and the output was verified successfully.
