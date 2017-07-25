#include<iostream>
#include <stdio.h>
using namespace std;
float x;
float y;

int wybor;



int main()

{
	cout<<" podaj liczbe: 1";
   cin>> x;
	cout<<"podaj liczbe 2";
	cin>> y;
	
	cout<<endl;
	cout<<"menu glowne"<<endl;
	cout<<"1. Dodawanie"<< endl;
	cout<<"2. odejmowanie"<<endl;
	cout<<"3. mnozenie"<<endl;
   cout<<"4. dzielenie"<<endl;
	cout<<endl;
	
   cout<<"wybierz:";
	cin>> wybor;
   switch (wybor)
	{
		case 1:
		{
			cout<<"wynik:"<< x << "+"<< y<< "="<<x+y<<endl;
			}
break;
		case2:
		{
		cout<<"wynik:"<<x<<"-"<<y<<"="<<x-y << endl;
	}
		break;
		case 3:
		{
			cout<<"wynik:"<<x<<"*"<<y<<"="<<x*y<<endl;
			}
break;
			case 4:
			{
			cout<<"wynik:"<<x<<"/"<<y<<"="<<x/y<<endl;
				}
			
				break;
	default:cout<<"nie ma takiej opcji w menu"<<endl;
			}
	
	return 0;
}
