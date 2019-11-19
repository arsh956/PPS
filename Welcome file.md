![College  Logo](https://www.gndec.ac.in/logo.png)
# *PPS Assignment*
## ***Submitted By :***
##### ***Name : Arshmeet***
##### ***Roll no. : 1921016***
##### ***Branch : Information technology (I.T.)***
##### ***Section : I.T. A1***

### ***Submitted To:- Ms. Ranjodh Kaur***

# My C programs
## 1. Odd even
```
#include<stdio.h>
int main()
{
int n;
printf("Enter a number: ");
scanf("%d",&n);                                            if(n % 2 == 0)
printf("The number is even");
else
printf("The number is odd");
}



```
**OUTPUT**
```
Enter a number: 5
The number is odd
```
## 2. Table
```
#include<stdio.h>
int main()
{
int num,i;
printf("enter the number: ");
scanf("%d",&num);
for(i=1;i<=20;i++)
printf("\n%d*%d=%d",num,i,num*i);
}
```
**Output**
```
enter the number: 7

7*1=7
7*2=14
7*3=21                                                     7*4=28
7*5=35
7*6=42
7*7=49
7*8=56
7*9=63
7*10=70
7*11=77
7*12=84
7*13=91
7*14=98
7*15=105
7*16=112
7*17=119
7*18=126
7*19=133
7*20=140
```
## 3. Table of even number
```
#include<stdio.h>
int main()
{
int n,i;
printf("enter a number");
scanf("%d",&n);
if(n % 2 == 0)
{
for(i = 0; i <= 10; i++)
{
printf("\n%d*%d=%d",n,i,n*i);
}
}
else                                                       {
printf("the number is not even");
}
return 0;
}
```
**Output**
```
enter a number6

6*0=0
6*1=6
6*2=12
6*3=18
6*4=24
6*5=30
6*6=36
6*7=42
6*8=48                                                     6*9=54
6*10=60
```
## 4.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY0MDIyNzY1LC04NjU4MzUwMDksMTA2ND
kzNTc3MCw1Mjk3MDk0MDEsLTIwODg3NDY2MTIsODYwNjkyNTM2
XX0=
-->