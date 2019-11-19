---


---

<h2 id="hello-world-program">1:Hello world Program</h2>
<pre><code>//To print  hello world
#include&lt;stdio.h&gt;
int main()
{                     
 printf("\nHello world\n");
}
</code></pre>
<p>OUTPUT:</p>
<pre><code> Hello world
</code></pre>
<h2 id="sum-and-average-of-numbers">2:Sum and Average of numbers</h2>
<pre><code> // sum and average of number
#include&lt;stdio.h&gt;
  int main()
 {                                 
     int a,b,c,d,e,sum,avg;
                                                               
   printf("Enter five numbers:");
   scanf("%d %d %d %d %d",&amp;a,&amp;b,&amp;c,&amp;d,&amp;e);
    sum = a+b+c+d+e;
   printf("The sum is:%d\n",sum);
   avg = sum/5;
   printf("The average is:%d\n",avg);
  }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter five numbers:1 2 3 4 5 
The sum is:15
The average is:3
</code></pre>
<h2 id="to-fill-your-information">3:To fill your information</h2>
<pre><code>  // To fill your information
#include&lt;stdio.h&gt;
  void info();
  int main()
  {
     info();
  }
   void info()
  {  char a[20];
     int roll,age;
     long int ph;
   printf("\nEnter your information:\n");
   printf("Name = ");
    scanf("%s",a);
  printf("\nRoll no=");
scanf("%d",&amp;roll);
printf("\nAge = ");
 scanf("%d",&amp;age);
 printf("\nPhone no.= ");
 scanf("%ld",&amp;ph);
printf("\nThe name is %s\nYour roll no is %d\nMy phone number is %ld\n My age is %d\n",a,roll,ph,age);
}
</code></pre>
<p><strong>OUTPUT:</strong></p>
<pre><code>Enter your information:
Name = Arshmeet
Roll no=
Age = 
Phone no.= 
The name is 
Your roll no is 
My phone number is 
 My age is
</code></pre>
<h2 id="to-show-areaperimetervolume-of-square">4:To show area,perimeter,volume of square</h2>
<pre><code>//Area,premiter,volume of square
#include&lt;stdio.h&gt;
void square();
int main()
{     
square();
return 0;
}                                    
void square()
{
int side;
printf("Enter the side of square:");
scanf("%d",&amp;side);
printf("\nPerimeter of square:%d",4*side);
printf("\nArea of square:%d",side*side);
printf("\nVolume of square:%d\n",side*side*side);
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the side of square:3
Perimeter of square:12
Area of square:9
Volume of square:27
</code></pre>
<h2 id="to-find-sum-of-two-numbers">5:To find sum of two numbers</h2>
<pre><code>     // to find sum of two numbers
     #include&lt;stdio.h&gt;
int main()
{                                                                                      
 int a;
 int b;
 int c ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&amp;a,&amp;b);
 c=a+b;
 printf(" \nThe result is :%d + %d= %d\n",a,b,c);
    return 0;
 }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter two numbers to get sum:10 20
 
The result is :10 + 20= 30
</code></pre>
<h2 id="to-find-number-is-even-or-odd">6:To find number is even or odd</h2>
<pre><code>     #include&lt;stdio.h&gt;
int main()
{                                
  int a;   
 printf("Enter a number:");
 scanf("%d",&amp;a);
if(a%2==0)
printf("The  number is even\n");
else
 printf("The number is odd\n");
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter a number : 6
The  number is even
</code></pre>
<p><em><strong>OR</strong></em></p>
<pre><code>Enter a number:7
The number is odd
</code></pre>
<h2 id="to-show-the-size-of-intfloatchardoublelongshort">7:To show the size of int,float,char,double,long,short</h2>
<pre><code> // size of int, float, char, double, long, short
#include&lt;stdio.h&gt;
int main()
{                                   
 printf("Integer:%d\n",sizeof(int));
 printf("float:%d\n",sizeof(float));
 printf("character:%d\n",sizeof(char));
 printf("double:%d\n",sizeof(double));
 printf("short:%d\n",sizeof(short));
 printf("long:%d\n",sizeof(long));
 }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Integer:4
float:4
character:1
double:8
short:2
long:8
</code></pre>
<h2 id="to-show-areadiametercircumference-of-circle">8:To show area,diameter,circumference of circle</h2>
<pre><code>#include&lt;stdio.h&gt;
 int main()
  {
    float a;   
float  const pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&amp;a);
  printf("diameter of circle is:%f\n",2*a);
  printf("circumference of circle:%f\n",2*pi*a);
  printf("Area of circle:%f\n",pi*a*a);
return 0;
 } 
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter radius of circle:2
diameter of circle is:4.000000
circumference of circle:12.560000
Area of circle:12.560000
</code></pre>
<h2 id="to-show-puts-value-upto-n-number-using-loop">9:To show puts value upto n number using loop</h2>
<pre><code>// to show punishment using loop
 #include&lt;stdio.h&gt;
 int main()
 {
 int i,a;
 printf("Enter the number upto punishment is shown:");
 scanf("%d",&amp;a);
  for(i=1;i&lt;=a;i++)
puts(" HARD WORK IS KEY TO SUCCESS ");
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the number upto punishment is shown:8
HARD WORK IS KEY TO SUCCESS
HARD WORK IS KEY TO SUCCESS
HARD WORK IS KEY TO SUCCESS
HARD WORK IS KEY TO SUCCESS
HARD WORK IS KEY TO SUCCESS
HARD WORK IS KEY TO SUCCESS
HARD WORK IS KEY TO SUCCESS
HARD WORK IS KEY TO SUCCESS

</code></pre>
<h2 id="to-find-area-and-volume-of-rectangle">10:To find area and volume of rectangle</h2>
<pre><code>//find area and volume of rectangle
#include&lt;stdio.h&gt;
int main()
{
 int l,b,h;
 printf("Enter length of rectangle:");
 scanf("%d",&amp;l);
 printf("\nEnter breadth of rectangle:");
 scanf("%d",&amp;b);
 printf("\nEnter height of rectangle:");
 scanf("%d",&amp;h);
 printf("\nThe area of rectangle is:%d",l*b);
 printf("\nThe volume is :%d\n",l*b*h);
 return 0;
 }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter length of rectangle:4 
Enter breadth of rectangle:3 
Enter height of rectangle:4
The area of rectangle is:12
The volume is :48
</code></pre>
<h2 id="to-show-even-table">11:To show even table</h2>
<pre><code>//To show only even table
#include&lt;stdio.h&gt;
int main(){
int a;
printf("tabel of:");
scanf("%d",&amp;a);
if(m%2==0)
{
for(int i=0;i&lt;=10;i++)
{
printf("%d X %d=%d\n",a,i,a*i);
}}
else
printf("enter even number\n");
return 0;}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>tabel of:3
3 X 0=0
3 X 1=3
3 X 2=6
3 X 3=9
3 X 4=15
3 X 5=15
3 X 6=18
3 X 7=21
3 X 8=24
3 X 9=27
3 X 10=30

</code></pre>
<h2 id="to-show-stars-pattern">12:To show stars pattern</h2>
<pre><code> // TO show stars using loop 
#include&lt;stdio.h&gt;
int main()
{ int i,j,k;
 printf("Enter the no. to show pattern:");
 scanf("%d",&amp;k);
 
  for(i=k;i&gt;=1;i--)
 {
  for(j=i;j&gt;=1;j--)
 {
  printf("* ");
 }
 printf("\n");
 }
 return 0;
 }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the no. to show pattern:8
* * * * * * * * 
* * * * * * * 
* * * * * * 
* * * * * 
* * * * 
* * * 
* * 
*
</code></pre>
<h2 id="to-convert-fahrehnite-to-celcius">13:To convert Fahrehnite to Celcius</h2>
<pre><code>//to convert fahrehnite to celcius
#include&lt;stdio.h&gt;
int main(){
float f,c;
printf("Enter temp in fahrehnite :");
scanf("%f",&amp;f);
c=((f-32)*5)/9;
printf("The celcius value is:%f\n",c);
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter temp in fahrehnite :450
The celcius value is:232.222229
</code></pre>
<h2 id="to-represent-a-table-of-user-input">14:To represent a table of user input</h2>
<pre><code> // To represent a table of user input  number
#include&lt;stdio.h&gt;
int main()
{
   int i,j,k;
 printf("Table of:");
 scanf("%d",&amp;j);
  for(i=0;i&lt;=10;i++)
  printf("%d x %d = %d\n",j,i,j*i);
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>15 x 0 = 0
15 x 1 = 15
15 x 2 = 30
15 x 3 = 45
15 x 4 = 60
15 x 5 = 75
15 x 6 = 90
15 x 7 = 105
15 x 8 = 120
15 x 9 = 135
15 x 10 = 150
</code></pre>
<h2 id="to-show-the-table-range">15: To show the table range</h2>
<pre><code>//To show a range of table upto user input
#include&lt;stdio.h&gt;
int main()
{
 int a,b,n;
 printf("table of:");
 scanf("%d",&amp;a);
 printf("\n enter the starting value of range:");
 scanf("%d",&amp;b);
 printf("\n enter the last value of range:");
 scanf("%d",&amp;n);
 for(b;b&lt;=n;b++)
 printf("%d x %d = %d\n",a,b,a*b);
 return 0;
 }
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>table of:5
 enter the starting value of range:20
 enter the last value of range:30
5 x 20 = 100
5 x 21 = 105
5 x 22 = 110
5 x 23 = 115
5 x 24 = 120
5 x 25 = 125
5 x 26 = 130
5 x 27 = 135
5 x 28 = 140
5 x 29 = 145
5 x 30 = 150
</code></pre>
<h2 id="to-call-a-patterns-of-face-and-calculator">16:To call a patterns of face and calculator</h2>
<pre><code>// call a pattern of face or calculator
             #include&lt;stdio.h&gt;
void calculator();
void face();
int main()
{  int a;
 printf("enter 0 to see a calculator or 1 to see face\n");
 scanf("%d",&amp;a);
if(a==0)
{
   calculator();
}
   else if(a==1)
{
     face();
  }
 else
{
  printf("enter correct values\n");
}
}
 void calculator()
{ 
puts(" _______________");
puts("|               |");
puts("|_______________|");
puts("| 1 | 2 | 3 |   |");
puts("|___|___|___|   |");
puts("| 4 | 5 | 6 | + |");
puts("|___|___|___|___|");
puts("| 7 | 8 | 9 | - |");
puts("|___|___|___|___|");
puts("|     0     | * |");
puts("|___________|___|");
}
 
 void face()
{
puts("___________________");
puts("|   XXXXXXXXXXX   |");
puts("|   ( ^     ^ )   |");
puts("|   ( 0     0 )   |");
puts("|    \\   |   /    |");
puts("|     \\     /     |");
puts("|      \\ = /      |");
puts("|       \\_/       |");
puts("|        |        |");
puts("|________|________|");
}
</code></pre>
<p><strong>OUTPUT</strong>:IF YOU ENTER 0 THEN OUTPUT IS :</p>
<pre><code>enter 0 to see a calculator or 1 to see face
0
 _______________
|               |
|_______________|
| 1 | 2 | 3 |   |
|___|___|___|   |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
|     0     | * |
|___________|___|
</code></pre>
<p>IF YOU ENTER 1 THEN OUTPUT</p>
<pre><code>enter 0 to see a calculator or 1 to see face
1
___________________
|   XXXXXXXXXXX   |
|   ( ^     ^ )                    |
|   ( 0     0 )                   |
|    \   |   /                       |
|     \     /                     |
|      \ = /      |
|       \_/       |
|        |        |
|________|________|
</code></pre>
<h2 id="to-show-factorial-result">17:To show factorial result</h2>
<pre><code>//To show factorial of user input
#include&lt;stdio.h&gt;
int main()
{
int a,result=1;
printf("Enter the factorial of:");
scanf("%d",&amp;a);
for(int i=a;i&gt;=1;i--)
{
printf("%d X ",i);
result=result*i;
}
printf("= %d\n",result);
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the factorial of:5
5 X 4 X 3 X 2 X 1 X = 120
</code></pre>
<h2 id="matrix-multipication">18:Matrix multipication</h2>
<pre><code>#include&lt;stdio.h&gt;
int main()
{
int sum=0,m,n,p,q,c,d,k;
int first[10][10], second[10][10], multiply[10][10];
// for matrix 1
printf("Enter the number of rows and column of first matrix:\n");
scanf("%d %d",&amp;m,&amp;n);
printf("Enter elements of first matrix:\n");
for(c=0;c&lt;m;c++)
for(d=0;d&lt;n;d++)
 scanf("%d",&amp;first[c][d]);
// for second matrix
printf("Enter the number of rows and columns of second matrix:\n");
scanf("%d %d",&amp;p,&amp;q);
if(n!=p){
printf("matrix multipication cannot be possible !!!!\n");}
else{
printf("Enter the elements of second matrix:\n");
for(c=0;c&lt;p;c++)
for(d=0;d&lt;q;d++)
 scanf("%d",&amp;second[c][d]);
for(c=0;c&lt;m;c++)
{
for(d=0;d&lt;q;d++)
{
 for(k=0;k&lt;p;k++)
{                             
 sum = sum + first[c][k] * second[k][d];
 }
  multiply[c][d] = sum;
sum =0;
}
}
 printf("product of the matrix:\n");
 
 for(c=0;c&lt;m;c++)
{
 for(d=0;d&lt;q;d++)
  printf("%d\t",multiply[c][d]);
  printf("\n");
}
}                             
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the number of rows and column of first matrix:
2 2
Enter elements of first matrix:
3 4
5 6
Enter the number of rows and columns of second matrix:
2 2
Enter the elements of second matrix:
1 2
3 4
product of the matrix:
15      22
23      34
</code></pre>
<h2 id="to-show-result-of-operands">19: To show result of operands</h2>
<pre><code>//To show results using operands(+,-,*,%,/)
#include&lt;stdio.h&gt;
int main()
{
float a,b;
 char c;
printf("enter first  number:");
scanf("%f",&amp;a);
printf("enter operator[+ - % / *]:");
scanf(" %c",&amp;c);
printf("enter second number:");
scanf("%f",&amp;b);
int d,r;
d=(int) a;
r=(int) b;
switch(c)
{
case '+': printf("The result is:%.2f\n",a+b); break;
case '-':printf("The result is:%.2f\n",a-b); break;
case '*':printf("The result is:%.2f\n",a*b); break;
case '%':printf("The result is:%d\n",d%r); break;
case '/':printf("The result is:%.2f\n",a/b); break;
default : printf("Enter correct operator ");
}
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>enter first  number:20
enter operator[+ - % / *]: *
enter second number:10
The result is:200.00
</code></pre>
<h2 id="to-show-stars-pattern-1">20:To show stars pattern</h2>
<pre><code>//to show star pattern for n numbers
#include&lt;stdio.h&gt;
int main()
{
int i,j,k;
printf("Enter the value upto pattern is shown:");
scanf("%d",&amp;k);
for(i=1;i&lt;=k;i++)
{
 for(j=1;j&lt;=i;j++)
{
 printf("* ");
}
printf("\n");
}
return 0;
}
</code></pre>
<p><strong>OUTPUT</strong>:</p>
<pre><code>Enter the value upto pattern is shown:8
* 
* * 
* * * 
* * * * 
* * * * * 
* * * * * * 
* * * * * * * 
* * * * * * * *
</code></pre>

