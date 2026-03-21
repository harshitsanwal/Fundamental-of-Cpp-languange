# Functions
In C++, functions are self-contained blocks of code that perform a specific task. Think of them as "sub-programs" that you can call whenever you need them, preventing your main() function from becoming a giant, unreadable mess.

# The Anatomy of a Function
Every function in C++ requires four main components:

Return Type: The type of data the function sends back (e.g., int, double, string). If it returns nothing, use void.

Function Name: A descriptive name (using camelCase is standard in C++).

Parameters (Inputs): Variables passed into the function. If no input is needed, leave the parentheses empty ().

Function Body: The code inside the curly braces {} that executes the task.
# Why Use Functions?
DRY (Don't Repeat Yourself): Instead of writing the same logic five times, you write it once in a function and call it five times.

Abstraction: You don't need to know how sort() works to use it; you just need to know what it does.

Testing: It is much easier to test one small function than a 500-line program.
# Example
```cpp
#include<iostream>
using namespace std;
int power(int , int); //Function Delclaration/Prototype
int main()
{
    int a ,b;
 cout << "Enter the Number :";
 cin>>a;
 cout << "\n Enter the power of the Number :";
 cin>>b;
 int result=power(a,b); // Function Call
 cout<< a <<" to power " << b <<" is: "<< result << endl;
 return 0;
}
int power(int a ,int b) // Function Defination
{
    int n=1;
    for(int i=1;i<=b;i++)
    {
        n=n*a;
    }
    return n;
}
```
```
Enter the Number :13

 Enter the power of the Number :2

 Power of 13 to power 2 is: 169
```
