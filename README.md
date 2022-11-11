#include<stdio.h>
#include<stdlib.h>
struct student
{
	int x,y;

}d,d1;
main()
{
	int s;
	d.x=5;
	d.y=2;
	s=d.x+d.y;
	d1.x=10;
	d1.y=12;
	printf("Sum=%d\n",s);
	printf("Sum=%d",d1.x+d1.y);
}
