# C-practice
1.MONTHS IN A YEAR
#include<iostream.h>
#include<conio.h>
void main()
{
int i;
cout<<"Enter the value of i(1-12):";
cin>>i;
switch(i)
{
case 1:cout<<"January";
   Break;
case 2:cout<<"February";
   Break;
case 3:cout<<"march";
  Break;
case 4:cout<<"April";
 break;
case 5:cout<<"May";
 break;
case 6:cout<<"June";
 break;
case 7:cout<<"July";
 break;
case 8:cout<<"August";
 break;
case 9:cout<<"September";
  break;
case 10:cout<<October";
 break;
case 11:cout<<"November";
 break;
case 12:cout<<"December";
 break;
default:cout<<"you have entered the wrong choice";
break;

}

getch();

}




2.

Ques 2)PRIME NUMBERS
#include <iostream.h> 
int main() {
	int n, i, flag;
    int u,j;

	cout<<"Enter Lower Limit :";
	cin>>n;
    cout<< "\nEnter Upper limit :";
    cin>>u;
for ( j=n; j<=u; ++j)
    {
        flag=0;
	for(i=2;i<=j/2;++i) { 
		if(j%i==0) { 
			flag=1; 
		} 
            }

	if (flag==0)
		cout<<n<<endl;
            
        }
	return 0;
}
3.GRADE LIST
#include<iostream.h>
#include<conio.h>
void main()
{
float grpt;
cout<<"Enter grade point(0-5):";
cin>>grpt;

if(grpt==5.0)
{
cout<<"Grade:O";
}
else if(grpt<5.0&&grpt>=4.5)
{
cout<<"Grade:A";
}
else if(grpt<4.5&&grpt>=4.0)
{
cout<<"Grade:B";
}
else if(grpt<4.0&&grpt>=3.0)
{
cout<<"Grade:C";
}

else if(grpt<3.0&&grpt>=2.0)
{
cout<<"Grade:D";
}
else if(grpt<2.0&&grpt>=1.0)


{

cout<<"Grade:E";
}
else 
cout<<"Grade:F";
 getch();
}


Ques 4)LEAP YEAR
#include <iostream.h>
#include <math.h>

int main()
{
    int year;
    cout<<"Enter year:";
    cin>>year;
    if (year<=1000)
    cout<<"\nInvalid argument";
    else
    if (year%4==0)
    cout<<"\nLeap year";
    else
    cout<<"\nNot a Leap Year";
    return 0;
}
5)Rainbow spelling


Ques 6)DIGIT
#include <iostream.h>
#include <math.h>

int main()
{
    int dig,key,z;
    int count=0;
    cout<<"Enter Digit:";
    cin>>dig;
    cout<<"\nEnter Key:";
    cin>>key;
    while(dig>0)
    {
        z=dig%10;
        if (z==key)
        count=count+1;
        dig=dig/10;
    }
    cout<<"The key appeared %d times",count;
    return 0;

Ques 10)LUCKY NUMBERS
#include <iostream.h>
#include <math.h>

int main()
{
    int num,x,z;
    cout<<"Enter No.:";
    cin>>num;
    int sum=0;
    if ((num<1000) || (num>9999))
    {
        cout<<"Invalid Arguement";
    
        }
    z=num;
    while (z>0)
       {
        x=z%10;
        sum=sum+x;
        z=z/10;
    }
    if ((sum%3==0) || (sum%5==0) || (sum%7==0))
    cout<<"Lucky No. is"<<num;
    else
    cout<<"Unlucky no.";
    return 0;
}
}



