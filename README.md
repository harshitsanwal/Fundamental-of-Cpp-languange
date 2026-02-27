# Fundamental-of-Cpp-languange
# Basic Syntax 
# Hello World Program
```cpp
#include<iostream>
using namespace std;
int main()
{
{
    cout<<"Hello World"<<endl;
    cout<<"Welcome to my first code of C++\n"; 
    cout<<"learning C++"; 
    return 0;
}
```
# Takin value from user
```cpp
#include<iostream>
using namespace std;
int main()
{
int i;
cout << "Enter a number:";
cin >> a;
cout<< "The entered number is:<< a <<endl;
return 0;
}
```
# variable in cpp
```cpp
#include<iostream>
using namespace std;
int main()
{
   int a=18;
   cout<< "Value of a is: " <<a<<endl;//printing interger value with some text
   cout<< a <<endl;//printing interger value
   char b='H';
   cout<< b <<endl;//printing character value
   float c=3.14;
   cout<< c <<endl;
   cout<< "Value of pi is: "<<c<<endl;//printing float value with some text
   bool h1=true;
   bool h2 = false;
   cout<< h1 <<endl;
   cout<< h2 <<endl;
   cout<< "Value of h1 is: "<<h1<<endl;//printing boolean value
   cout<< "Value of h2 is: "<<h2<<endl;//printing boolean value
   int size=sizeof(c);
   cout<<"Sizee of c is: "<<size<<endl;//printing size of variable  
   return 0;
}
```
# Conditional statement 
```cpp
#include<iostream>
using namespace std;
int main()
{
    int n;
    cout << "Enter the number:";
    cin >> n;
    if(n%2==0)
    {
        cout << "The number "<< n << " is even." <<endl;
    }
    else
    {
        cout <<"The number "<< n <<" is odd."<< endl;
    }
    return 0;
}
```
# Printing the sum of n Natural number
```cpp
#include<iostream>
using namespace std;
int main()
{
    int n,sum=0;
    cout << "Enter the number :";
    cin >> n;
    while(n>0)
    {
        sum=sum+n;
        n--;
    }
    cout << "The sum of n natural numbers is: " << sum << endl;
    return 0;
}
```
# A Simple Calculator
```cpp
#include<iostream>
using namespace std;
int main()
{
int num1,num2,i;
cout<< "Enter the first number:";
cin>>num1;
cout<<"Enter the second number:";
cin>>num2;
cout<<"Press 1 for Addition"<<endl;
cout<<"Press 2 for Subtraction"<<endl;
cout<<"Press 3 for multiplication"<<endl;
cout<<"Press 4 for Division"<<endl;
cin>>i;
if(i==1)
cout<<"Addition of 2 number is :-"<<num1+num2<<endl;
else if(i==2)
cout<<"Subtraction of 2 number is :-"<<num1-num2<<endl;
else if(i==3)
cout<<"Multliplication of 2 number is:-"<<num1*num2<<endl;
else if(i==4)
cout<<"Division of 2 number is:-"<<num1/num2<<endl;
else
cout<<"Enter choice is invalid"<<endl;
return 0;
}
```

 
