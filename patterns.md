# Different Patterns in Cpp
# 1 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int i=0,n,j,k=1;
    cout << "Enter the number: ";
    cin >> n;
    while(i<n)
    {
        j=0;
        while(j<n)
        {
            cout<< n-j+1;
            j++;
            
        }
        cout<<endl;
        i++;
    }
    return 0;
}
```
# 2 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int n,i=1,j,k=1;
    cout << "Enter the number: ";
    cin>> n;
    while(i<=n)
    {
        j=1;
        while(j<=n)
        {
            cout <<" " <<  k;
            j++;
            k++;
        }
        cout << endl;
        i++;
    }
    return 0;
}
```
# 3 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int n,i=1,j,k=1;
    cout << "Enter the number: ";
    cin>> n;
    while(i<=n)
    {
        j=1;
        while(j<=n)
        {
            cout <<" " <<  k;
            j++;
            k++;
        }
        cout << endl;
        i++;
    }
    return 0;
}
```
# 4 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int n,i=0,j;
    cout << "Enter the number: ";
    cin>> n;
    while(i<n)
    {
        j=0;
        while(j<n)
        {
            if(j<=i)
            {
                cout << "*";
                j++;
            }
            else{
                cout << " ";
                j++;
            }
        }
        cout << endl;
           i++; 
    }
    return 0;
}
```
# 5 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int i=0,n,j,k=1;
    cout << "Enter the number: ";
    cin>> n;
    while(i<n)
    {
        j=0;
        while(j<n)
        {
            if(j<=i)
            {
               cout << k;
            } 
            else{
                cout << " ";
            }
            j++;
        }
        cout << endl;
        k++;
        i++;
    }
    return 0;
}
```
# 6 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
	int i=0,j,n,k=1;
	cout << "Enter the number: ";
	cin >> n;
	while(i<n)
	{
		j=0;
		while(j<n)
		{
			if(j<=i)
			{
				cout << " " << k;
				k++;
			}
			else
			{
				cout << " ";
			}
			j++;
		}
		cout << endl;
		i++;
	}
	return 0;
}
```
# 7 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,i=1,j,k=1,m=1;
	cout << "Enter the number:";
	cin >> n;
	while(i<n)
	{
		j=1;
		while(j<n)
		{
		 if(j<=i)
			{
			cout << k;
			k++;
			j++;
		    }
			else
			{
				cout <<" " ;
				j++;
			}
		
		}
		cout << endl;
		i++;
		k=i;
	}	
		return 0;
}
```
# Pattern 8
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,i=1,j,m=0;
	cout << "Enter the number:" ;
	cin>> n;
	while(i<n)
	{
		j=1;
		while(j<n)
		{
			if(j<=i)
			{
				m=i-j+1;
				cout << m;
				j++;
			}
			else
			{
				cout << " ";
			    j++;
			}
		}
		cout << endl;
		i++;
	}
	return 0;
```
# Pattern 9
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,i=1,j;
	cout << "Enter the number:" ;
	cin>> n;
	while(i<n)
	{
		j=1;
		while(j<=i)
        {
            cout << (i-j+1);
            j++;
        }
        cout << endl;
        i++;
    }   
    return 0;
}
```
# Pattern 10
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,i=0,k=1;
	cout<<"Enter the number of rows:" ;
	cin>> n;
    for(i=0;i<n;i++)
    {
    	for(int j=0;j<n;j++)
    	{
    		if(j<=i)
    		{
    			cout<< " "<< k;
    			k++;
			}
		else
		cout<< " ";	
		}
	   k=i;
		cout << endl;
	}
	return 0;
}
```
# Pattern 11
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,k=1;
	cout<< "enter the number of rows:";
	cin>> n;
	for(int i=1;i<=n;i++)
	{
		for(int j=1;j<=n;j++)
		{
			if(j<=i)
			{
				cout<<" "<<k;
				k--;
			}
			else
			cout<< " ";
		}
		k=i;
		cout<<endl;
	}
	return 0;
}
```

