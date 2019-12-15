![](https://ce.gndec.ac.in/sites/default/files/logo.jpg)
# *PPS Assignment*
## ***Submitted By :***
##### ***Name : Arshmeet***
##### ***Roll no. : 1921014***
##### ***University Rollno : 1905310***
##### ***Branch : Information technology (I.T.)***
##### ***Section : I.T. A1***

### ***Submitted To:- Ms. Ranjodh Kaur***

# My C programs
## 1. To check whether Number is odd or even.
```C
#include<stdio.h>
int main()
{
int n;
printf("Enter a number: ");
scanf("%d",&n);
if(n % 2 == 0)
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
## 2. Program to display table of user choice.
```C
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
## 3. Table of even number.
```C
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
## 4. To display the table between range.
```C
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
## 5. To convert temperature from Fahrenheit to celcius.
```C
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
```C
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
## 7. To check the number is prime or not.
```C

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
## 8. To check whether number is negative or positive.
```C
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
```C
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
##  10 Program using switch case.
```C
#include<stdio.h>
int main()
{
int a,b,c,choice;
printf("\n1. plus (+) operator");
printf("\n2. minus (-) operator");
printf("\n3. multiply (*) operator");
printf("\n4. modulas (%) operator");                       printf("\n\n Enter your choice");
scanf("%d",&choice);
switch(choice)
{
case 1:                                                    printf("Enter two numbers: ");
scanf("%d %d",&a,&b);
c = a+b;
printf("\n The sum is %d",c);
break;
case 2:
printf(" Enter two numbers: ");
scanf("%d %d",&a,&b);
c = a-b;
printf(" \nThe subtraction of %d and %d is %d",a,b,c);     break;
case 3:
printf("Enter two numbers: ");
scanf("%d %d",&a,&b);
c = a*b;
printf("\nThe multiplication of %d and %d is %d",a,b,c);
break;
case 4:
printf("Enter two numbers: ");
scanf("%d %d",&a,&b);
= a % b;
printf("\nThe modulas of %d and %d is %d",a,b,c);
break;
default :
printf("Invalid choice");
}
}
```
**Output**
```
1. plus (+) operator
2. minus (-) operator
3. multiply (*) operator
4. modulas (%) operator
```
## 11.Program using function with no argument and no return value.
```
#include<stdio.h>
int evenodd();
int add();
int thanks();
int main()
{
add();
evenodd();
thanks();
}
int evenodd()
{
int x;
printf("enter a number");
scanf("%d",&x);
if(x % 2 == 0)
printf("The number is even\n");
else
printf("The number is odd\n");
return 0;
}
int add()
{
int a,b,c;
printf("\nenter two numbers");
scanf("%d %d",&a,&b);
c = a+b;
printf(" sum is %d\n",c);
return 0;
}
int thanks()
{
printf("\nTHANKS\n");
return 0;
}
```
**output**
```
enter two numbers4 5
 sum is 9
enter a number91
The number is odd

THANKS
```
## 12. Program using Function with argument and no return value.
```
#include<stdio.h>
void add(int,int);
void main()
{
int x,y;
printf("enter two numbers");
scanf("%d %d",&x,&y);
add(x,y);
}
void add(int a, int b)
{
int c;
c= a+b;
printf(" sum is %d",c);
}
```
**Output**
```
enter two numbers45 56
 sum is 101
 ```
 ## 13.Program using function with no argument and return value
 ```
 #include<stdio.h>
int add();
int main()
{
int s;
s = add();
printf("sum is %d",s);
}
int add()
{
int a,b,c;
printf("enter two numbers");
scanf("%d %d",&a,&b);
c = a+b;
return c;
}
```
**Output**
```
Enter a number45 56
sum is 101
```
## 14.Program using function with argument and with return value
```
#include<stdio.h>
int add(int,int);
int main()
{
int s,x,y;
printf("Enter a number");
scanf("%d %d",&x,&y);
s = add(x,y);
printf("sum is %d",s);
return 0;
}
int add(int a,int b)
{
int c;
c = a+b;
return c;
}
```
**output**
```
enter two numbers32 67
sum is 99
```
## 15.Program to find largest number.
```
#include<stdio.h>
int main()
{
int a,b,c,big;
printf("Enter three numbers: ");
scanf("%d %d %d",&a,&b,&c);
if(a>b)
if(a>c)
big=a;
else big=c;
else if(b>c)
big=b;
else big=c;
printf("Largest of %d %d %d = %d",a,b,c,big);
}
```
**output**
```
Enter three numbers: 34 23 45
Largest of 34 23 45 = 45
```
## 16.Program to find diameter,area,circumference of circle.
```
#include<stdio.h>
int main()
{
float a;
float const pi = 3.14;
printf("Enter the radius of circle");
scanf("%f",&a);
printf("diameter of circle is %f\n",2*a);
printf("circumference of circle is %f\n",2*pi*a);
printf("area of circle is %f\n",pi*a*a);
return 0;
}
```
 **Output**
 ```
 Enter the radius of circle:5
diameter of circle is 10.000000
circumference of circle is 31.400002
area of circle is 78.500000
```
## 17.Program to find matrix using array.
```

#include<stdio.h>
int main()
{
int a[3][3],b[3][3],c[3][3],i,j;
printf("enter 9 numbers of first array");
for(i=0;i<=2;i++)
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
printf("enter 9 numbers of second array");
for(i=0;i<=2;i++)
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
{
c[i][j]=a[i][j]+b[i][j];
printf("%d",c[i][j]);
}
printf("\n");
}
return 0;
}
```
**Output**
```
enter 9 numbers of first array2
1
0
3
2
4
5
2
0
enter 9 numbers of second array2
4
7
1
4
2
1
0
2
457
466
622
```
## 18.Program to find factorial of number.
```
#include<stdio.h>
int main()
{
int i,n,c=1;
printf("enter a number");
scanf("%d",&n);
for(i=1;i<=n;i++)
c=c*i;
printf("the factorial of %d =%d\n",n,c);
return 0;
}
```
**Output**
```
enter a number6
the factorial of 6 =720
```
## 19.Program to find factorial of number using recursion.
```
#include<stdio.h>
int fact();
int main()
{
int i,x;
printf("enter a number:");
scanf("%d",&x);
i = fact(x);
printf("factorial is %d\n",i);
return 0;
}
int fact(int a)
{
int s;
if(a==1)
return(a);
s = a * fact(a-1);
return(s);
}


```
**Output**
```
enter a number:7
factorial is 5040
```
## 20.Program to find sum of n natural numbers using recursion.
```

#include<stdio.h>
int sum();
int main()
{
int i,x;
printf("enter a natural number");
scanf("%d",&x);
i = sum(x);
printf("sum of %d natural numbers is %d\n",x,i);
return 0;
}
int sum(int a)
{
int s;
if(a==1)
return(a);
else
s = a+sum(a-1);
return(s);
}
```
**Output**
```
enter a natural number10
sum of 10 natural numbers is 55
```
## 21.Program to print n odd numbers of user choice and to find their sum.
```
#include<stdio.h>
int main()
{
int i,n,sum=0;
printf("enter a number ");
scanf("%d",&n);
for(i=1;i<=n;i++)
{
if(i % 2 != 0)
{
printf("%d\n",i);
sum = sum + i;
}
}
printf("sum of odd natural numbers between 1 and 100 is %d",sum);
return 0;
}
```
**Output**
```
enter a number 50
1
3
5
7
9
11
13
15
17
19
21
23
25
27
29
31
33
35
37
39
41
43
45
47
49
sum of odd natural numbers between 1 and 100 is 625
```








