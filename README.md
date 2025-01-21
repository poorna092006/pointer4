//wap to demonstrate the use of a pointer to pointer
#include <stdio.h>
int main()
{
	int x=20;
	int *p;
	int **q;
	p=&x;
	q=&p;
	printf ("The value of x is %d \n",**q);
	return 0;
}
