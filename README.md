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
#Printing the sum of n Natural number
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



