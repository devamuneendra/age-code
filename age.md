#include<stdio.h>
#include<conio.h>
int main()
{
	int age;
	char name;
	printf("enter your age and name\n");
	scanf("%d%c",&age,&name);
	printf("my age is %d \n my name is %c",age,name);
	getch();
	return 0;
}
