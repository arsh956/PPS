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
## 2.Marks
```
#include <stdio.h>                                         int main ()
{
char name[50];
int marks,i,n;
printf("Enter number of students");
scanf("%d",&n);
for(i=0;i<n;++i){
printf("forstudent%d/nEnter name:",i+1);
scanf("%s,name");
printf("Enter marks: ");
scanf("%d",&marks);
printf("\nName: %s,\nmarks=%d\nname,marks");               }
return 0;
}
```
**OUTPUT **
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5OTIxMzkxMjEsNTI5NzA5NDAxLC0yMD
g4NzQ2NjEyLDg2MDY5MjUzNl19
-->