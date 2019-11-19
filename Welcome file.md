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
## 4. To print the table between range
```
#include<stdio.h>                                          int main()                                                 {                                                          int n1,n2,i,j;
printf("enter first number: "),
scanf("%d",&n1);
printf("enter second number: ");
scanf("%d",&n2);
for(i=n1;i<=n2;i++)
{
for(j=1;j<=10;j++)
{
printf("%d*%d=%d\n",i,j,i*j);
}                                                          }
}
```
**Output**
```
enter first number: 5                                      enter second number: 6
5*1=5
5*2=10
5*3=15
5*4=20
5*5=25
5*6=30
5*7=35
5*8=40
5*9=45                                                     5*10=50
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
## 5. To convert temperature from Fahrenheit to celcius
```
#include<stdio.h>
int main()
{
float f,c;
printf("enter the temperature in fahrenheit: ");
scanf("%f",&f);                                            c=((f-32)*5)/9;
printf("temperature in celcius is %f",c);
}
```
**Output**
```
enter the temperature in fahrenheit: 53
temperature in celcius is 11.666667
```
## 6. Star pattern
```
#include<stdio.h>
int main()
{
int n;
printf("Enter the no:");
scanf("%d",&n);
int i,j;
for( j = 1;j <= n; j++)
{
for( i = 1;i <= j; i++)
{ printf("*");
}
printf("\n");
}
}
```
**Output**
```
Enter the no:5
*
**
***
****
*****
```
## 7. To check the number is prime or not
```

#include<stdio.h>
int main()
{
int i,n,remainder = 1;
printf("enter a number");
scanf("%d",&n);
for(i = 2; i <= n/2; i++)
{
if(n % i == 0)                                             {
remainder = 0;
break;
}
}
if(remainder == 1)
{
printf("%d number is prime",n);
}
else
{
printf("%d is not a prime number",n);
}
```
**Output**
```
enter a number11
11 number is prime
```
## 8. Number is negative or positive
```
#include<stdio.h>
int main()
{
int n;
printf("Enter a number: ");
scanf("%d",&n);
if(n<0)
printf("The number is negative");
else
printf("The number is positive");
}
```
**Output**
```
Enter a number: 5
The number is positive
```
## 9. Fizzbuzz
```
#include<stdio.h>
int main()
{
int n;
printf("Enter the integer:");
scanf("%d",&n);
if(n%3==0)
printf("\nFizz");
if(n%5==0)
printf("Buzz\n");
else
printf("\n%d",n);                                          return 0;
}
```
**Output**
```
Enter the integer:5
Buzz
```
##  10 Factorial of a number
#include  <stdio
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcwMzE4NTAzMywxMTMwOTA3MTIzLDQwNj
A3MzYzNSwxMTI0MjcxOTk2LC04NjU4MzUwMDksMTA2NDkzNTc3
MCw1Mjk3MDk0MDEsLTIwODg3NDY2MTIsODYwNjkyNTM2XX0=
-->