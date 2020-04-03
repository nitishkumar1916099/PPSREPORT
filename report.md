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

