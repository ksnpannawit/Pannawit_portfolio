#include<iostream.h>
#include<conio.h>

int m, f; //m=mid f=final
char cal();
void input();
int sum();


void main()
	{
	clrscr();
	input();
	cout<<"Sum Score = "<<sum()<<endl;
	cout<<"Grade = "<<cal();
	getch();
	}
void input()
		{
		cout<<"Mid Term Score ";
		cin>>m;
		cout<<"Final Term Score ";
		cin>>f;
		}
int sum()
		{
		return(m+f);
		}
char cal()
		{
		int total=sum();
		if(total<=49)
		return'F';
		else if (total<=59)
		return'D';
		else if (total<=69)
		return'C';
		else if (total<=79)
		return'B';
		else if (total<=100)
		return'A';
		else if (total>100)
		return'E';
		return(total);
		}
