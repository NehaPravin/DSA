#include<stdio.h>
#include<stdlib.h>
int queue[5],f=-1,r=-1;
void rear();
void front();
void show();
int main()
{
	int ch;
	printf("1.Rear \n");
	printf("2.Front \n");
	printf("3.Show \n");
	printf("4.Exit \n");
	while(1)
	{
		printf("\n enter your Choice:");
		scanf("%d",&ch);
		switch(ch)
		{
			case 1:
				rear();
				break;
			case 2:
			front();
			break;
				case 3:
					show();
					break;
			case 4:
			exit(0);
			break;
				default:
				printf("invalid Option");		
					
		}
	}
}
void rear()
{
	int item;
	if(r==5-1)
	{
		printf("queue is full");
	}
	else
	{
		if(f==-1)
		{
			f=0;
		}
		printf("Insert elemet in queue");
		scanf("%d",&item);
		r=r+1;
		queue[r]=item;
	}
}
void front()
{
	if(f==-1)
	{
	printf("queue is empty");	
	}
	else
	{
		printf("Deleted %d",queue[f]);
		f=f+1;
	}
}
void show()
{
	int i;
	if(f==-1)
	{
		printf("queue is empty");
	}
	else
	{
		printf("queue elemnt \n");
		for(i=f;i<=r;i++)
		{
			printf("%d",queue[i]);
		}
	}
}










