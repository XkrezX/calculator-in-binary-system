# calculator-in-binary-system
#include <iostream>
#include <math.h>
using namespace std;
char maxInd[256];
char* buff(const char* text);
int chv1();
int chv2();
int chv2(int d);
int main()
{
int p1, p2;
int c, d, dd, a, b;
while (c!=0)
{
cout<<("What action do you want to perform?")<<endl;

cout<<("1-addition")<<endl;

cout<<("2-subtraction")<<endl;

cout<<("3-division")<<endl;

cout<<("4-multiplication")<<endl;
  
cout<<("0-Exit")<<endl;
cin >> c;
switch (c)
{
case 1:
{
p1 = chv1();
p2 = chv2();
d=p1+p2;
chv2(d);
cout << endl;
}
break;
case 2:{
p1= chv1();
p2 = chv2();
d=p1-p2;
chv2(d);
cout << endl;
}
break;
case 3:{
p1 = chv1();
p2 = chv2();
d=p1/p2;
chv2(d);
cout << endl;
}
break;
case 4:{
p1 = chv1();
p2 = chv2();
d=p1*p2;
chv2(d);
cout << endl;
}
break;
}
