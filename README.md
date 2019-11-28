# Pri
TO CHECK A NUMBER IS PRIME OR NOT 
#include<iostream.h>
#include<conio.h>
#include<stdio.h>
void main()
{
clrscr();
int x,i;
cout<<"Enter the Number:";
cin>>x;
for(i=2;i<=x;i++)
{
  if(x % i==0)
  {
   cout<<"It is a PRIME NUMBER";
  }
  else
  {
  cout<<"It is not a PRIME NUMBER";
   }
}
else
{
cout<<"It is not a PRIME NUMBER";
}
getch();
}
