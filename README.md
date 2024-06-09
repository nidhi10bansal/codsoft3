# codsoft3
#include<iostream>  //an simple basic calculator
using namespace std;
int main()
{ double x,y;
char a;
cout<<"Hello mate, Welcome!"<<endl;
cout<<"Enter first number:";        //take input from user of 2 nos. and an operation to perform and the chosen operation to be performed.
cin>>x;
cout<<"Enter second number:";
cin>>y;
cout<<"Choose an operation to perform:";
cin>>a;
switch(a)
{ case '+': cout<<"The result is:"<<x+y<<endl;
break;
case '-': cout<<"The result is:"<<x-y<<endl;
break;
case '*': cout<<"The result is:"<<x*y<<endl;
break;
case '/': cout<<"The result is:"<<x/y<<endl;
break;
default: cout<<"Error!Input operator incorrect."<<endl;
break;}
return 0;
}

