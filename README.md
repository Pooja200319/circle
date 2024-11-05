#include<stdio.h>
int area(int);
int circumference(int);
it diameter(int);
int main()
{
int r;
printf("ente the radius of circle:\n");
scanf("%d",&r);
printf("result of area= %d \n",area(r))
printf("result of circumference= %d \n",circumference(r))
printf("result of diameter= %d \n",diameter(r));
return 0;
}
int area(int radius)
{
        return (3.14*r*r);
}
int circumference(int radius)
{
       return (2*3.14*r);
}
