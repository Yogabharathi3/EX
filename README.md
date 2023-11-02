# EX-05-5c-ARRAYS AND ITS OPERATIONS
## AIM:
Write C Program to find Sum of each row of a Matrix
## ALGORITHM:
1. Declare and initialize the matrix with the desired values.
2. Create a loop to iterate through each row of the matrix.
3. Inside the loop, calculate the sum of the elements in each row.
4. Print the sum for each row.
## PROGRAM:
```
#include<stdio.h>
int main()
{
int a,b,sum1=0,sum2=0,sum3=0;
scanf("%d %d",&a,&b);
int arr[a][b];
for(int i=0;i<a;i++)
{
for(int j=0;j<b;j++)
{
scanf("%d",&arr[i][j]);
}
}
for(int i=0;i<a;i++)
{
for(int j=0;j<b;j++)
{
if(i==0)
sum1+=arr[i][j]
else if(i==1)
sum2+=arr[i][j]
else
sum3+=arr[i][j]
}
}
printf("The Sum of Elements of a Rows in a Matrix: %d\n",sum1);
printf("The Sum of Elements of a Rows in a Matrix: %d\n",sum2);
printf("The Sum of Elements of a Rows in a Matrix: %d\n",sum3);
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/EX/assets/118899387/547abdc6-e82c-449c-a121-9e7148ead433)

## RESULT:
Thus the program to find Sum of each row of a Matrix has been executed successfully.
