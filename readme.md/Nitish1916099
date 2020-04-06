![gne logo](https://www.gndec.ac.in/sites/default/logo.png)
# programming for problem solving(ESC-105)
------------------
Sbmitted by-Nitish kumar

College Roll Number-1916099

University Roll Number-1905128

Branch-Electrical Engineering

Section-B

Batch:2019-2023

-------------
Experiment-1:write a code to print name
```C
#include<stdio.h>
int main()
{
printf("Nitish Kumar");
}
```
--------------
Experiment-2:print FOX
```C
#include<stdio.h>
int main()
{
    puts("########    ########      ####        ####");
    puts("##      ####        ####    ###     ###");
    puts("##      ####        ####      ###  ###");
    puts("######  ####        ####        ####");
    puts("##      ####        ####       ### ###");
    puts("##      ####        ####      ###   ###");
    puts("##          ########        ####      ####");
}
```
--------------
Experiment-3:write a program to display "hello"
```C
#include<stdio.h>
int main()
{
    puts("hello");
}
```
-----------
Experiment-4:Design a code to execute addition of two numbers.
 ```C 
 #include<stdio.h>
int main()
{
    int a,b,c;
    puts("enter two number");
    scanf("%d %d",&a,&b);
    c=a+b;
    printf("%d",c);
    return 0;
}
```
--------------
EXPERIMENT-5:Write a computer program in C, which takes two numbers (integers) as input and print the smaller number.
```C
#include<stdio.h>
int main()
{
    int a,b;
    puts("enter two number for comparison");
    scanf("%d %d",&a,&b);
    if(a<b)
    printf("the smaller number is %d",a);
    else
    printf("the smaller number is %d",b);
    return 0;
}
```
-------------------
Experiment-6:Write a program that prints fizz if a number is even and prints buzz if a number is odd.
```C
#include<stdio.h>

int main()
{
    int a;
    scanf("%d",&a);
    if(a%2 == 0)
    {
      printf("fizz");}
    else
    {
    printf("buzz");}
    return 0;
}
```
----------------
Experiment-7:program of FizzBuzz
```C
#include<stdio.h>
int main()
{
printf("\t----FizzBuzz----\n");
int i,n;
printf("\n\nSelect the range in which you want to play : ");
scanf("%d",&n);
for(i=1;i<=n;i++)
{
if(i%15==0)
{
printf("\nFizzBuzz");
}
else if(i%5==0)
{
printf("\nBuzz");
}
else if(i%3==0)
{
printf("\nFizz");
}
else
{
printf("\n%d",i);
}
}
return 0;
}
```
----------------
Experiment-8:program of game of life
```C
#include<stdio.h>
int main()
{
printf("\t---Conway's Game of Life---\n\n");
int neighbouringcell;
printf("\n\nEnter the number of Neighbouring cells : ");
scanf("%d",&neighbouringcell);
if(neighbouringcell==3)
{
printf("\nThe dead cell will become live in the next generation\n");
}
else if(neighbouringcell<=1)
{
printf("The alive cell will die in next generation\n");
}
else if(neighbouringcell>=2 && neighbouringcell<=3)
{
printf("The living cell will reamain alive in the next generation\n");
}
else
{
printf("The alive cell will die due to overpopulation in next generation\n");
}
return 0;
}
```
-------------------

Experiment-9:
Write a computer program in C, to print nth term, and sum up to nth term for sine
series.
```C
#include<stdio.h>
int main()
{
int i, n;
float x, deg, numerator, denominator, term ,temp=1, sum=0;
printf("Enter the value of x in degree : ");
scanf("%f",&deg);
printf("Enter the value of n : ");
scanf("%d",&n);
x=deg*3.141/180;
numerator=x;
denominator=1;
sum=x;
for(i=2;i<=n;i++)
{
numerator=numerator*x*x;
denominator=denominator*(i*2-2)*(i*2-1);
temp=temp*(-1);
term=numerator/denominator*temp;
sum=sum+term;
}
printf("\nThe sum is %.3f",sum);
return 0;
}
```
------------------
Experiment-10:)Write a computer program in C, which take integer input from user. If entered value > 10, it will call a function, which
prints multiplication table of of entered number, from 1 to 10, in following format:
1 x 7 = 7
2 x 7 = 14
If entered value is between 6 to 10, then will be call another function, which print number of lines equal to entered number
in following pattern:
#
#.#
#...#
#.....#
#.......#
for any other input it will display:
Have a nice day!
```C
#include<stdio.h>
void table(int n)
{
int i;
for(i=1;i<=10;i++)
{
printf("\n%d X %d = %d",i,n,i*n);
}
}
void pattern(void)
{
puts(" #");
puts(" #.#");
puts(" #...#");
puts(" #.....#");
puts("#.......#");
}
void string(void)
{
puts("Have a nice day!");
}
int main()
{
int n;
printf("Enter a positive integer : ");
scanf("%d",&n);
if(n>=6 && n<=10)
{
table(n);
}
else if(n>10)
{
pattern();
}
else
{
string();
}
return 0;
}
```
-------------
